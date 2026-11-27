# AnswerLock 答题解锁

An answer-to-unlock parental control app for Android — kids solve study questions to earn screen time. Turn "how long can I play" into "learn first, then play for a while."

English | [简体中文](./README.md)

## Download

| File | Description |
| --- | --- |
| [answerlock_v0.6.1_mobile.apk](./answerlock_v0.6.1_mobile.apk) | Phone / tablet build (Android, arm64 + v7a + x86_64, ~24.8 MB) |
| [answerlock_v0.6.1_tv.apk](./answerlock_v0.6.1_tv.apk) | Android TV build (all ABIs, ~24.8 MB) |
| [答题解锁_v0.6.1_使用说明书.html](https://github.com/yuanduo2015/answerlock/blob/master/答题解锁_v0.6.1_使用说明书.html) | Full user manual (Chinese, opens offline, printable to PDF; use this GitHub link if Gitee blocks it) |
| [答题锁_家长版产品说明.html](./答题锁_家长版产品说明.html) | One-page product intro for parents (Chinese, easy to read and share) |

- Current version: **v0.6.1** (2026-11-28: typing books split into 16 per-grade books — grade 1-6, junior 1-3, senior 1-3, college 1-4 — each with IPA for every word; new "continue quizzing" reward: answer 3 more questions to get +3 extra minutes; fixed v0.6.0's invisible white-on-white chip text on the study content page; darker overview header and more legible gray hint text. ⚠️ v0.6.0 was withdrawn because of that text bug — use v0.6.1)
- Phone SHA256: `F855C45BAC29AB3AB65C013BABA77A0F137C2DB49D87F6918AF72A3BFE083C60`
- TV SHA256: `4341E52C9D5CE32E04BAD25B3DC6C9CE9CDCCCDB57323B5DE8479EB2284AE035`
- ⚠️ **Signing note**: v0.3.65+ is signed with the official key. When upgrading from v0.3.63/0.3.64, please uninstall the old version first (uninstalling clears local answers and settings); v0.3.65 and later upgrade over the top as usual.

## Quick start

1. **Install** — download the APK on the phone and open it (allow "install unknown apps" when prompted).
2. **5-minute setup** — set a 6-digit parent PIN, pick grade / subjects / difficulty, then enable Accessibility, Device Admin and other permissions until every indicator turns green.
3. **Start supervision** — choose the entertainment apps to limit, tap "开始答题" (Start Quizzing), and return to the home screen. When your child opens a restricted app, they will be asked to answer questions before the app unlocks.

Note: the app interface and manual are currently Chinese-only; the steps above cover the essentials.

## Highlights

- **English typing practice (v0.5.0 / v0.6.1, phone / tablet)** — card-based word typing: each level has 8 words, shown briefly (3 s by default, adjustable 1.5/3/5/8 s) then hidden, and the child types them on the built-in on-screen keyboard with per-letter validation (correct letters turn green, mistakes flash red); includes “listen” and “peek” helpers. Pass to earn stars, retry wrong words immediately afterwards; first 2+ star pass of a level each day grants 5 extra minutes of unlocked time. Since v0.6.1 there is one book per grade (16 books, every word with IPA), grouped by stage with the current grade pinned on top
- **Continue-quizzing reward (v0.6.1)** — after unlocking, the child may tap "I want to keep going: 3 more questions, +3 minutes"; answering 3 more correctly adds 3 extra minutes on top of the parent-set time (still counted against the daily limit)
- **College grades & CET-4/6 banks (v0.5.0)** — pick freshman to senior; subjects are English / Safety, with a 300-question CET English bank per grade (freshman selections never draw senior questions)
- **Answer to unlock** — answer the required number of questions to earn a play session; wrong answers add extra questions (configurable 0–5) and go to a mistake notebook for review
- **Safety Classroom (v0.4.0, free)** — the safety bank spans 5 stages (primary / junior / senior / adult / senior citizens) with **2756 questions** (284 sensitive-content questions removed as of v0.4.4), all free: blended into kids' quizzes (~1 in 5), a dedicated "Safety" difficulty card, and a family self-test that never consumes the child's quota; content written from public safety materials by the Ministry of Public Security and related authorities
- **Time counts only when actually used (v0.3.59)** — play time is settled by actual usage: minutes not played before a parent takeover are refunded to the daily quota, and the in-app child-mode preview no longer consumes the child's quota
- **Game-friendly interception** — if the timer runs out mid-game, the app waits until the match ends (settlement / exit / background) before showing questions, avoiding hard interruptions; capped at 30 min on phones, 15 min on TVs (Standard edition)
- **Four anti-uninstall defenses** — device admin + accessibility guard + foreground service + auto-restart recovery
- **Self-service PIN recovery** — set a security question from "Change Password" in parent settings (gently prompted when changing the PIN, skippable), then reset the parent PIN yourself if forgotten, no support ticket needed
- **Phone / tablet / TV** — tablets get an automatic large-screen layout; the TV build works fully by remote control and adapts to different TV brands and screen sizes
- **Younger-kid friendly (v0.3.56)** — pinyin annotations on questions/answers for grades 1–2; a “read the question / read the answer” button on the quiz page
- **Rich question bank (v0.3.66)** — all 66 banks now hold 150+ questions each; Pro enables "question bank expansion" by default for 10,000 questions in total; distractors are length-calibrated so correct answers no longer stand out visually
- **Data stays on the device** — no sign-up, no cloud collection; uninstalling the app removes all local data

## Version & support

- The free edition covers the core flow (up to 2 restricted apps, 10 blocks per day); Pro is ¥99/year, ¥249 for 3 years or ¥399 lifetime (one-time purchase) — to upgrade, contact support on WeChat: **hiyuanmi2015**
- Upgrading the app — v0.3.65+ uses the official signing key: when upgrading from older builds, uninstall first and install fresh; later versions can be installed over the previous one with rules and records kept on the device.

---

AnswerLock is a parental-supervision tool for managing children's screen time. Please set reasonable quiz counts and time limits, and agree on the rules with your child in advance.

> AI生成