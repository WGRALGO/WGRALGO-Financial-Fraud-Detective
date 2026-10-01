# Changelog

## v1.1.0

- New case library from the updated web game: 45 realistic cases covering
  identity theft, cars, contractors, loans, credit and debt, taxes, benefits,
  immigration and legal help, cards and checks, home and property, and small business.
- Evidence is shown the way you'd really see it: text threads, emails, phone-call
  transcripts, web pages, mailed letters, and in-person situations.
- Balanced rounds: 4 beginner / 4 intermediate / 2 advanced, 5 fraud + 5 legit.
- Feedback now includes "What to do in real life" for every case.
- Results: detective rank, weak spots by category, and an expandable case file.
- New native-style app design (app bar, progress bar, bottom action buttons,
  score ring, slide-up About / Privacy / Credits sheets).
- Added a Content-Security-Policy; removed the website "Request a Workshop" link.
- **New release signing key.** Uninstall v1.0.0 before installing v1.1.0.
- Added GitHub Actions: debug build on every push and a signed release workflow.
- Added `tools/validate-release.sh` (`npm run validate`).
- Version 1.0.0 → 1.1.0 (versionCode 100 → 110).

## v1.0.0

- Initial GitHub-ready Android APK release.
- Added offline fraud-detection educational game.
- Added case-based Fraud / Looks Legit gameplay with random 10-case sessions drawn from a 100+ case pool.
- Added beginner / intermediate / advanced difficulty levels.
- Added case categories: text, message, phone call, email, investment offer, payment app, job offer, bank alert.
- Added instant feedback, red flag explanations, and safety tips.
- Added scoreboard, progress tracking, and final detective rating.
- Added Play Again to reset the game.
- Removed website navigation, social media widget, GoFundMe bar, and WordPress menu clutter from the APK interface.
- Updated package name to `org.wgralgo.financialfrauddetective`.
- Added GPLv3 license, privacy statement, contributors file, security policy, third-party notices, and README.
- Built with proper release signing (v1 + v2).
- Hardened offline/privacy posture: APK does not declare `INTERNET` permission.
