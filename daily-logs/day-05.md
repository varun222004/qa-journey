# 📅 Day 05 — Maestro Studio Deep Dive

**Date:** 2026-03-27
**Track:** 🧪 QA Automation — Maestro Studio

---

## ✅ What I Did Today
- Continued Maestro Studio learning — advanced commands
- Updated the Maestro Cheat Sheet with Use Cases column
- Understood the Studio vs CLI vs Cloud architecture

## 🧠 Concepts Learned
- All YAML commands work across Studio, CLI, and Cloud — only the runner changes
- `startRecording` is CLI-only — Studio limitation confirmed
- The difference between asserting visibility vs asserting a condition (`assertTrue`)
- Visual regression testing concept via `assertScreenshot`
- How `evalScript` lets you run JavaScript mid-test for dynamic logic

## 🛠️ New Commands Discovered
| Command | What it does |
|---------|-------------|
| `openLink` | Navigate to a URL mid-test |
| `repeat` | Loop a set of actions N times |
| `retry` | Auto-retry flaky steps |
| `extendedWaitUntil` | Wait for a specific element with custom timeout |
| `assertTrue` | Assert a custom condition is true |
| `assertScreenshot` | Visual baseline comparison |
| `setClipboard` | Set clipboard text directly |
| `evalScript` | Run JavaScript inside a Maestro flow |
| `label` | Add custom name to test steps for readability |
| `optional` | Mark a step so test doesn't fail if element is missing |

## 📦 Deliverables Created
- Updated Maestro Cheat Sheet with Use Cases column
- Updated pressKey Reference with Use Cases
- Updated Quick Reference card

## 🗺️ What's Still Left to Learn
- [ ] CLI execution
- [ ] Screen recording via CLI
- [ ] runFlow / subflows
- [ ] evalScript in a real flow
- [ ] Environment variables
- [ ] repeat + retry in a real scenario
- [ ] assertScreenshot baseline testing
- [ ] CI/CD integration

## 🎯 Tomorrow's Goal
- Try CLI execution for the first time
- Build a flow using `repeat` and `retry` on a real scenario

## 💭 Thoughts
The fact that the same YAML works on Studio, CLI, and Cloud is huge.
Learn once, run anywhere. That's the kind of scalability that matters
in real SDET work. Also — `evalScript` is where things get really
powerful. That's next on my list. 🚀
