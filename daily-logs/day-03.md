# 📅 Day 03 — Edge Case Thinking

**Date:** 2026-03-25
**Track:** 🧪 QA / Work

---

## ✅ What I Did Today
- Wrote and executed test cases for "Auto refresh homescreen
  10 mins before a consultation call" feature
- Explored edge cases around the feature behaviour

## 🧠 What I Learned
- Edge case thinking is about asking "what if everything
  goes wrong at the exact worst moment?"
- Real-world user flows are rarely straight paths —
  always test the boundaries

## 🐛 Edge Case I Found
- **Scenario:** User is already online before the 10-min
  mark AND the doctor cancels the consultation exactly
  at the 10-min trigger point
- **Why it matters:** The auto-refresh may still fire even
  though the consultation no longer exists — could cause
  a broken screen or misleading UI state
- **Severity:** Medium — affects real users waiting for calls

## 🎯 Tomorrow's Goal
- Explore more edge cases on the same feature
- Think about: what if the user has no internet at the
  10-min mark?

## 💭 Thoughts
Edge cases are where the real bugs live. Anyone can test
the happy path — good QA engineers hunt the edges. 🧪
