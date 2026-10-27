# Case studies

Draft — figures are taken from the worklog (verifiable in commit history and
linked repos). Verify before sending to a client.

## 1. Lesson production pipeline for a working ESL practice

**Problem.** A teaching practice needs multi-stage lessons, vocabulary blocks,
answer keys and per-student homework every week. The platform has no public API,
so every lesson was assembled by hand in the UI.

**What was built.** A spec-driven CLI over the platform's private WebSocket RPC
(`cli-edvibe`): 17 exercise types, lesson and homework builders that take a JSON
spec. Format knowledge from 31 platform FAQ articles was encoded as rules for 26
exercise templates, so an agent can generate valid exercises instead of
approximating the syntax.

**Outcome.** A 27-block B2 lesson (5 stages, hidden answer keys) built from a
video in one pass, and its 6-exercise homework attached to a live sheet with one
command, verified on the platform.

## 2. Turning a Minecraft server into an English curriculum

**Problem.** An ESL Minecraft server had no progression model — play time did
not map to language level, and rewards were disconnected from learning.

**What was built.** Four Paper plugins (~2,500 lines of Java, Vault + LuckPerms):
earnings-driven rank progression, level-filtered vocabulary quizzes, daily
craft/plant/collect quests tuned per CEFR level, and AI-scored chat rewards.
Progression was later split into two independent axes: rank from lifetime
earnings, CEFR from a 25-question placement test with listening audio.

**Outcome.** Levels stopped collapsing below their starting value, 13 NPC quests
that previously hung were fixed, and a mirrored build gate verified 1,763 of
1,792 cells before release.

## 3. Course analytics and progress reporting

**Problem.** No visibility into whether students actually progress: answers were
spread across a course platform, community chat and lesson records.

**What was built.** A read-only course scan feeding six progress cards, a
dashboard backed by a 4.6k-answer database, and a ranking of 15.7k community
messages into 10 recurring teacher pain points. An answer-engine visibility
tracker measures how often the brand is cited across 15 prompts and 90 citation
slots.

**Outcome.** Progress cards re-anchored to live data, goals counted in lessons
instead of calendar months, and a 0/15 baseline established for citation
tracking.

## How I work

- Ship small, verify against the real system, not against a mock.
- Automate the boring part, keep the teacher in the loop on judgement calls.
- Every claim here traces to a commit or a measurable check.
