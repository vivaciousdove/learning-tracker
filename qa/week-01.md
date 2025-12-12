# Week 01 — QA Foundations & Playwright CI

## 🎯 Focus
- Playwright UI testing
- GitHub Actions CI setup
- Evidence-driven testing (reports, traces, screenshots)

## 🧪 What I Practiced
- Ran Playwright tests locally and in CI
- Fixed headless browser issues in GitHub Actions
- Generated HTML reports and trace artifacts
- Verified artifacts download correctly from CI

## 🧠 Key Learnings
- CI environments require headless configuration
- Artifacts must be uploaded with `if: always()`
- A passing test without evidence is incomplete

## 📎 Evidence
- GitHub Actions → Playwright Tests workflow
- Downloadable `playwright-report` artifact
- Trace viewer screenshots stored in repo

## ⏭️ Next Steps
- Add negative test scenarios
- Improve assertions around dynamic timestamps
- Refactor selectors for resilience
