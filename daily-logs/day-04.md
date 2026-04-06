# 📅 Day 04 — Maestro Studio Basics

**Date:** 2026-03-26
**Track:** 🧪 QA Automation — Maestro Studio

---

## ✅ What I Did Today
- Started learning Maestro Studio from scratch
- Understood YAML-based test structure and how Maestro works
- Built 5 complete E2E test flows on practicesoftwaretesting.com
- Created a Maestro Studio Commands Cheat Sheet (.xlsx)

## 🧠 Concepts Learned
- What Maestro is and how it differs from Selenium
- YAML test structure — how flows are written
- Difference between `appId` and `url`
- What `clearState` does and when to use it
- `Label` vs `Placeholder` — key lesson for element targeting
- How to read Maestro error messages
- What `assertVisible` actually validates in a QA context
- Screenshot as test evidence — documenting proof of pass/fail

## 🛠️ Commands Practiced
`launchApp` · `tapOn` · `inputText` · `assertVisible` · `assertNotVisible`
`waitForAnimationToEnd` · `scroll` · `scrollUntilVisible` · `swipe`
`takeScreenshot` · `pressKey` · `doubleTapOn` · `longPressOn`
`eraseText` · `clearText` · `copyTextFrom` · `pasteText`

## 🧪 Flows Built
- ✅ Login flow (full E2E)
- ✅ Registration form flow
- ✅ Add to cart flow
- ✅ Scroll + product navigation flow
- ✅ pressKey keyboard interaction flow

## 🐛 Bugs & Fixes I Hit
- `Element not found` → root cause: was targeting Label, not Placeholder
- `scrollUntilVisible` direction issue → debugged UP vs DOWN scroll direction
- `startRecording` broken in Studio → discovered it only works in CLI
- 0 byte mp4 file → confirmed Studio recording limitation

## 📦 Deliverables Created
- Maestro Studio Commands Cheat Sheet (All Commands + pressKey Reference + Quick Reference)
- Task ticket title + description for work

## 🎯 Tomorrow's Goal
- Dive deeper into advanced Maestro commands
- Explore `evalScript`, `repeat`, `retry`, and `assertTrue`

## 💭 Thoughts
Maestro's YAML structure is way more readable than Selenium Java.
The Label vs Placeholder bug cost me time but taught me more than
any tutorial would have. Real learning happens in the debug. 🧪
