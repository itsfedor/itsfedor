<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.png">
  <img alt="Fedor Molodtsov — AI Automation Engineer · ESL EdTech Builder" src="assets/banner-light.png" width="100%">
</picture>

<h1 align="center">Fedor Molodtsov · AI Automation Engineer</h1>

<p align="center">
  I build AI automations that ship — agent pipelines, integrations and tools that replace hours of manual work.
</p>

Everything in this account runs in production for a private ESL teaching practice
(thousands of lessons delivered): lesson generators, a voice-note → Notion student
tracker, AI-scored Minecraft plugins, interactive web demos.

**Currently building:** a video → lesson-guide pipeline (Deepgram transcription → normalizer → teacher's-guide generator) and an Edvibe lesson-building agent.

**Open to:** contract AI-automation work and remote roles (UTC+7).

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff" alt="Python" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=fff" alt="Java" />
  <img src="https://img.shields.io/badge/Notion%20API-000000?logo=notion&logoColor=fff" alt="Notion API" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=fff" alt="GitHub Actions" />
</p>

## Selected projects

| Project | What it does | Proof | Stack |
|---|---|---|---|
| [**ESL Automation Suite**](https://github.com/itsfedor/esl-automation-suite) | AI teaching pipelines: lesson-guide generator, voice → Notion student tracker, video-review summaries (Deepgram), TV-episode homework, Edvibe lesson builder | 6 pipelines · 3 installable agent skills | Python · LLM APIs · Notion · Deepgram |
| **ESL Minecraft plugins** — [chat2earn](https://github.com/itsfedor/chat2earn) · [englishprogression](https://github.com/itsfedor/englishprogression) · [vocabquiz](https://github.com/itsfedor/vocabquiz) · [dailyenglish](https://github.com/itsfedor/dailyenglish) | 4 PaperMC plugins that turn a Minecraft server into an English classroom: AI-scored chat payouts, earnings-driven level-ups, vocab quizzes, daily tasks | 4 plugins · ~2,500 lines of Java · Vault + LuckPerms | Java · PaperMC · Groq |
| [**ChainLuck**](https://github.com/itsfedor/demo-casino) | Provably-fair demo crypto casino — Dice, Plinko, Blackjack, Slots, Crash, Mines. Play money only | 6 games · machine-verified RTP (`rtp-check.mjs`) · [live demo](https://itsfedor.github.io/demo-casino) | Vanilla JS · GitHub Pages |
| [**Worklog**](https://github.com/itsfedor/worklog) | Daily log of what actually shipped, written by a scheduled agent | machine-readable · one entry per workday | Automation |

## Recent activity

<!-- WORKLOG:START -->
- **2026-10-08**: The teacher dashboard gained review read-receipts — server-recorded "opened / not opened" status per review (a student's own reads only; teacher view-as excluded), an "unopened" filter, and a 46-check QA suite in dormant + active modes; the refresh moved to weekdays at noon and a fresh scan deployed byte-identical to both edge nodes.
- **2026-10-07**: Teacher dashboard reworked — moved to itsfedor.cc/dashboard with English-first cards, compact status chips and teacher-gated avatars, smart back navigation, and a Mon/Wed/Fri scan; two new public repos published ([notion-charts](https://github.com/itsfedor/notion-charts), [esl-feedback-design-system](https://github.com/itsfedor/esl-feedback-design-system)); the account's READMEs slimmed to theme-adaptive banners; two spoken lessons built and live-verified; the platform's book folders repaired after a silent-detach quirk.
- **2026-10-06**: Built and live-verified the next B2 spoken lesson (the eighteenth verified build); the student area grew to every student with analyses — seven legacy reviews rebuilt to the current design canon, all suites green on production; closed the platform's entire homework queue (29 sheets, three new reviews published); launched the teacher dashboard at itsfedor.cc/progress/dashboard.
- **2026-10-05**: Portfolio re-audit + PII scrub (three histories rewritten, verified); [Prism landing](https://itsfedor.github.io/prism-landing/) and theme-adaptive banners shipped; a new B2 spoken lesson built and live-verified; the itsfedor.cc student area reworked — new IELTS review, privacy-hardened cabinet, and legal pages (/offer/, /privacy/) live.
- **2026-10-04**: The grammar series now opens on one merged "Module 1 · Tenses" in all ten books — 31 lessons moved, modules renumbered, every publishing surface re-synced.
<!-- WORKLOG:END -->

_Appended by a scheduled agent when there's real work to log. Full history: [worklog](https://github.com/itsfedor/worklog)._

## Get in touch

- GitHub: [@itsfedor](https://github.com/itsfedor)
- Telegram: [@itsfedor](https://t.me/itsfedor)
- Open to AI-automation and EdTech collaborations. Pick a repo, check the README, and let's talk.
