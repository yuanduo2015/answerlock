# AnswerLock 答题锁

An answer-to-unlock parental control app for Android — kids solve study questions to earn screen time. Turn "how long can I play" into "learn first, then play for a while."

English | [简体中文](./README.md)

## Download

| File | Description |
| --- | --- |
| [answerlock_v0.3.65_mobile.apk](./answerlock_v0.3.65_mobile.apk) | Phone / tablet build (Android, arm64 + v7a + x86_64, 22.8 MB) |
| [answerlock_v0.3.65_tv.apk](./answerlock_v0.3.65_tv.apk) | Android TV build (all ABIs, 22.8 MB) |
| [答题锁_v0.3.65_使用说明书.html](./答题锁_v0.3.65_使用说明书.html) | Full user manual (Chinese, opens offline, printable to PDF) |
| [答题锁_家长版产品说明.html](./答题锁_家长版产品说明.html) | One-page product intro for parents (Chinese, easy to read and share) |

- Current version: **v0.3.65** (2026-11-25: switched to our own official signing key — upgrading from older builds requires uninstalling once first; Pro question bank expanded to 150+ questions per bank, 10,000 in total; the parent-home "Today" card now bundles answer records, the mistake notebook and the update entry)
- Phone SHA256: `DF87085F9B332BDB49EAF877C1688384E357C1394987BFF66C5A5C56AC5E701C`
- TV SHA256: `E5D2148C8CEF48B4CBE33368348BB8504793F822E296702D6D1671015C62DFB0`
- ⚠️ **Signing note**: v0.3.65+ is signed with the official key. When upgrading from v0.3.63/0.3.64, please uninstall the old version first (uninstalling clears local answers and settings); all later versions upgrade over the top as usual.

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
- **Self-service PIN recovery** — set a security question from "Change Password" in parent settings (gently prompted when changing the PIN, skippable), then reset the parent PIN yourself if forgotten, no support ticket needed
- **Phone / tablet / TV** — tablets get an automatic large-screen layout; the TV build works fully by remote control and adapts to different TV brands and screen sizes
- **Younger-kid friendly (v0.3.56)** — pinyin annotations on questions/answers for grades 1–2; a “read the question / read the answer” button on the quiz page
- **Rich question bank (v0.3.65)** — all 66 banks now hold 150+ questions each; Pro enables "question bank expansion" by default for 10,000 questions in total
- **Data stays on the device** — no sign-up, no cloud collection; uninstalling the app removes all local data

## Version & support

- The free edition covers the core flow (up to 2 restricted apps, 10 blocks per day); Pro is ¥99/year, ¥249 for 3 years or ¥399 lifetime (one-time purchase) — to upgrade, contact support on WeChat: **hiyuanmi2015**
- Upgrading the app — v0.3.65+ uses the official signing key: when upgrading from older builds, uninstall first and install fresh; later versions can be installed over the previous one with rules and records kept on the device.

---

AnswerLock is a parental-supervision tool for managing children's screen time. Please set reasonable quiz counts and time limits, and agree on the rules with your child in advance.

> AI生成