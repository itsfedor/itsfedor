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
- **2026-10-14**: The public site shipped its frontend-design audit — seven fixes across six pages (an accessible badge red, real tap targets, a state-aware vote section, sentence-case legal headings), the teacher dashboard restyled on the Cirrus kit, and Meta's server-side event pairing closing the tracking-coverage gap; two new B2 lessons built and live-verified (a TED-Ed on isolation, an ABA entertainment-law interview) with the storefront stepping twice to 244 lessons; the platform's first course-book import pipeline stood up with two units verified live; a match-cell rendering bug class fixed across nine lessons; and the GitHub side got a maintenance pass — every workspace clone re-bound after the token rotation, six dead clones decommissioned.
- **2026-10-13**: The speaking course finished its cleanup — video duplicates out under the one-video-one-lesson rule, five lessons rebuilt at level, a six-lesson wave re-leveled into C1, and the migration's closing verification came back clean; two new B2 lessons built and live-verified; the "Engoo Daily News" book launched at 45 lessons with its public landing page at [itsfedor.cc/news](https://itsfedor.cc/news/); the books store gained a working two-currency checkout and the site a verified Meta Pixel across its four marketing pages.
- **2026-10-12**: The CLI projects were rebranded to the `cli-<platform>` convention — cli-edvibe and cli-langlisto, fully renamed with fresh art and every dependent surface deployed — and cli-langlisto went from first release to v2.0.0 in one day (18 more exercise types, a corrected homework model, 76 tests); the school's operating setup completed its move off Edvibe onto LangListo — all 12 student accounts re-verified by sign-in, 9 classes and the weekly schedule live — with the grammar series landing as platform books (154 lessons across four of five volumes), a fresh cover system, and seven new or re-homed speaking lessons built and verified.
- **2026-10-11**: The ESL Minecraft server's quest + level-progression system went from brainstorm to live world in one day — the full design set (a 12-quest storyline plus six progression gates), the NPC provider picked on jar-level evidence, a 19-file quest pack authored and load-tested clean on a local Paper sandbox, and the quest village generated on the live world with its progression counters; plus two admin prep packs staged from live state and ≈4.3 GB of workspace reclaimed.
- **2026-10-10**: The GitHub profile hero was rebuilt — the wide banner replaced by a theme-adaptive card grid (an identity card + the five pinned projects as landscape mini-banners with translucent accent tints), three design passes, verified live in both themes; a reusable local-business visibility-audit workflow (Maps-link resolution, listing scrape, AI-citation sweep, free levers) captured as a skill.
<!-- WORKLOG:END -->

_Appended by a scheduled agent when there's real work to log. Full history: [worklog](https://github.com/itsfedor/worklog)._

## Get in touch

- GitHub: [@itsfedor](https://github.com/itsfedor)
- Telegram: [@itsfedor](https://t.me/itsfedor)
- Open to AI-automation and EdTech collaborations. Pick a repo, check the README, and let's talk.
