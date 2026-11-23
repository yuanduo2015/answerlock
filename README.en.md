# AnswerLock 答题锁

An answer-to-unlock parental control app for Android — kids solve study questions to earn screen time. Turn "how long can I play" into "learn first, then play for a while."

English | [简体中文](./README.md)

## Download

| File | Description |
| --- | --- |
| [answerlock_v0.3.61_mobile.apk](./answerlock_v0.3.61_mobile.apk) | Phone / tablet build (Android, arm64 + v7a, 15.0 MB) |
| [answerlock_v0.3.61_tv.apk](./answerlock_v0.3.61_tv.apk) | Android TV build (all ABIs, 22.4 MB) |
| [答题锁_v0.3.61_使用说明书.html](./答题锁_v0.3.61_使用说明书.html) | Full user manual (Chinese, opens offline, printable to PDF) |
| [答题锁_家长版产品说明.html](./答题锁_家长版产品说明.html) | One-page product intro for parents (Chinese, easy to read and share) |

- Current version: **v0.3.61** (2026-11-23, same-day respin: fixed the built-in version constant not being synced, which caused a wrong version display and an endless update prompt)
- Phone SHA256: `7874F623AD798E62BBE254C209DB01FAF074F4002B563B9294D16EADAE78E6F4`
- TV SHA256: `7DDB9DC32462BBCA0DACA43B7C5C83DB5B453D6930C1E6315463F058A9EE0AF2`

## Quick start

1. **Install** — download the APK on the phone and open it (allow "install unknown apps" when prompted).
2. **5-minute setup** — set a 6-digit parent PIN, pick grade / subjects / difficulty, then enable Accessibility, Device Admin and other permissions until every indicator turns green.
3. **Start supervision** — choose the entertainment apps to limit, tap "开始答题" (Start Quizzing), and return to the home screen. When your child opens a restricted app, they will be asked to answer questions before the app unlocks.

Note: the app interface and manual are currently Chinese-only; the steps above cover the essentials.

## Highlights

- **Answer to unlock** — answer the required number of questions to earn a play session; wrong answers add extra questions (configurable 0–5) and go to a mistake notebook for review
- **Time counts only when actually used (v0.3.59)** — play time is settled by actual usage: minutes not played before a parent takeover are refunded to the daily quota, and the in-app child-mode preview no longer consumes the child's quota
- **Game-friendly interception** — if the timer runs out mid-game, the app waits until the match ends (settlement / exit / background) before showing questions, avoiding hard interruptions; capped at 30 min on phones, 15 min on TVs (Standard edition)
- **Four anti-uninstall defenses** — device admin + accessibility guard + foreground service + auto-restart recovery
- **Self-service PIN recovery** — set a security question at setup and reset the parent PIN yourself if forgotten, no support ticket needed
- **Phone / tablet / TV** — tablets get an automatic large-screen layout; the TV build works fully by remote control and adapts to different TV brands and screen sizes
- **Younger-kid friendly (v0.3.56)** — pinyin annotations on questions/answers for grades 1–2; a “read the question / read the answer” button on the quiz page
- **Rich question bank** — 50+ questions per difficulty for primary Chinese and English
- **Data stays on the device** — no sign-up, no cloud collection; uninstalling the app removes all local data

## Version & support

- The free trial edition covers the core flow (up to 2 restricted apps, 10 blocks per day); Standard is ¥99/year, ¥249 for 3 years or ¥399 lifetime (one-time purchase) — to upgrade, contact support on WeChat: **hiyuanmi2015**
- Upgrading the app — download the new APK and install over the previous version; rules and records are kept on the device.

---

AnswerLock is a parental-supervision tool for managing children's screen time. Please set reasonable quiz counts and time limits, and agree on the rules with your child in advance.

> AI生成