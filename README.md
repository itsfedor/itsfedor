<p align="center">
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/cards/about-dark.png"><img alt="Fedor Molodtsov — AI Automation Engineer and ESL EdTech builder (UTC+7)" src="assets/cards/about-light.png" width="48%"></picture>
  <a href="https://github.com/itsfedor/esl-automation-suite"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/cards/esl-automation-suite-dark.png"><img alt="ESL Automation Suite — six open-source AI teaching pipelines" src="assets/cards/esl-automation-suite-light.png" width="48%"></picture></a>
  <a href="https://github.com/itsfedor/cli-edvibe"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/cards/cli-edvibe-dark.png"><img alt="cli-edvibe — reverse-engineered CLI for Edvibe lessons and homework" src="assets/cards/cli-edvibe-light.png" width="48%"></picture></a>
  <a href="https://github.com/itsfedor/esl-feedback-design-system"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/cards/esl-feedback-design-system-dark.png"><img alt="ESL Feedback Design System — palette, slot-marked templates, linter and render QA" src="assets/cards/esl-feedback-design-system-light.png" width="48%"></picture></a>
  <a href="https://github.com/itsfedor/notion-charts"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/cards/notion-charts-dark.png"><img alt="Notion Charts — JSON specs rendered into Notion-style chart and table PNGs" src="assets/cards/notion-charts-light.png" width="48%"></picture></a>
  <a href="https://github.com/itsfedor/worklog"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/cards/worklog-dark.png"><img alt="Worklog — a daily log of real shipped work" src="assets/cards/worklog-light.png" width="48%"></picture></a>
</p>

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
| [**Worklog**](https://github.com/itsfedor/worklog) | Daily log of what actually shipped, written by a scheduled agent | machine-readable · one entry per workday | Automation |

## Recent activity

<!-- WORKLOG:START -->
- **2026-10-16**: The site's tracking gained audience segmentation — marketing-page events now carry a teachers/students category (server-side copies included; trial requests send hashed advanced matching with UTM journaling) and the privacy policy covers it; the footers were unified into one canon with legal links and requisites on every page, and an experimental Tailwind + Preline rebuild of the homepage shipped as its own reviewable draft page; on the platform side, a new B2 lesson ("Articles in work messages") was reworked into image-work tasks with hidden teacher notes under each mock, and the teacher dashboard's dead refresh plus the homepage's live-lesson indicator were fixed and redeployed.
- **2026-10-15**: The sales funnel went live end to end — an overnight push shipped a Telegram free-to-paid lead bridge (first real contacts arriving), server-side accounting for every Buy click, the Meta purchase and event gaps closed, and a new MCP bridge for direct messenger operations; the purchase flow was unified across every sales page (a two-route dialog with per-region pricing, card payments wired live) and the site cleaned up — dead sections out, live course cards, counters re-homed; the storefront stepped to 245 lessons / 58 speaking with a new B2 lesson ("The Hidden Backdoors Inside Your Smart Devices"); and the course-book pipeline added five more verified units.
- **2026-10-14**: The public site shipped its frontend-design audit — seven fixes across six pages (an accessible badge red, real tap targets, a state-aware vote section, sentence-case legal headings), the teacher dashboard restyled on the Cirrus kit, and Meta's server-side event pairing closing the tracking-coverage gap; two new B2 lessons built and live-verified (a TED-Ed on isolation, an ABA entertainment-law interview) with the storefront stepping twice to 244 lessons; the platform's first course-book import pipeline stood up with two units verified live; a match-cell rendering bug class fixed across nine lessons; and the GitHub side got a maintenance pass — every workspace clone re-bound after the token rotation, six dead clones decommissioned; the same evening the school's five-episode serial-video homework course was also mirrored to the platform — every lesson built, checked and verified.
- **2026-10-13**: The speaking course finished its cleanup — video duplicates out under the one-video-one-lesson rule, five lessons rebuilt at level, a six-lesson wave re-leveled into C1, and the migration's closing verification came back clean; two new B2 lessons built and live-verified; the "Engoo Daily News" book launched at 45 lessons with its public landing page at [itsfedor.cc/news](https://itsfedor.cc/news/); the books store gained a working two-currency checkout and the site a verified Meta Pixel across its four marketing pages.
- **2026-10-12**: The CLI projects were rebranded to the `cli-<platform>` convention — cli-edvibe and cli-langlisto, fully renamed with fresh art and every dependent surface deployed — and cli-langlisto went from first release to v2.0.0 in one day (18 more exercise types, a corrected homework model, 76 tests); the school's operating setup completed its move off Edvibe onto LangListo — all 12 student accounts re-verified by sign-in, 9 classes and the weekly schedule live — with the grammar series landing as platform books (154 lessons across four of five volumes), a fresh cover system, and seven new or re-homed speaking lessons built and verified.
<!-- WORKLOG:END -->

_Appended by a scheduled agent when there's real work to log. Full history: [worklog](https://github.com/itsfedor/worklog)._

## Get in touch

- GitHub: [@itsfedor](https://github.com/itsfedor)
- Telegram: [@itsfedor](https://t.me/itsfedor)
- Open to AI-automation and EdTech collaborations. Pick a repo, check the README, and let's talk.
