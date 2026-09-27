# Second Brain Starter (PARA + Zettelkasten)

An **Obsidian vault template**: **PARA** for action, **Zettelkasten** for long-term knowledge. Open this folder in Cursor and the agent follows root `AGENTS.md`.

Traditional Chinese README: [README.md](README.md)

---

## How to get this template

1. On GitHub click **Use this template** and create **your** repository. Do not push your diary into this public template.
2. `git clone` your repo, then Obsidian → **Open folder as vault** on the repo root.
3. If notes may be sensitive, keep **your** repository **Private**.

License: [MIT](LICENSE). Bundled community plugins: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

---

## Folder map

1. **`0-Inbox`** — Quick capture. Empty it **weekly**. See [WeeklyInboxRitual.md](7-Templates/WeeklyInboxRitual.md).
2. **`1-Projects`** — Work with a goal and an end date. Move to `4-Archives` when done.
3. **`2-Areas`** — Ongoing responsibilities with no single deadline (health, money, a craft).
4. **`3-Resources`** — Reference material, reading notes, assets.
5. **`4-Archives`** — Finished or no-longer-active items. Keep them findable, out of daily view.
6. **`5-Zettelkasten`** — One idea per note, in your own words, linked with `[[wikilinks]]`. Do not paste whole articles.
7. **`6-DailyNotes`** — `YYYY-MM-DD.md` daily notes. Link back to projects and zettels.
8. **`7-Templates`** — Daily, Inbox, Zettel, project, and weekly-inbox templates.

Unsure where it goes → `0-Inbox`.

---

## Day one: Obsidian

1. **Open folder as vault** → this repository root.
2. **Settings → Core plugins**
   - Enable **Templates** → folder `7-Templates`
   - Enable **Daily notes** → new files in `6-DailyNotes`, template `7-Templates/DailyNoteTemplate.md`
3. Write
   - Daily note: sidebar calendar or “Open today's daily note” (if Calendar is enabled).
   - Templates: `Cmd/Ctrl + P` → `Insert template`.

Vault onboarding: [Getting Started.md](Getting%20Started.md) · 中文：[如何開始使用.md](如何開始使用.md)

---

## Day one: Cursor (preinstalled)

This starter already includes:

- Root `AGENTS.md`
- `.cursor/rules/second-brain-vault.mdc`
- `.cursor/skills/obsidian-markdown/`

Open the **same vault root** in Cursor. Install notes: [README-安裝到Cursor.md](7-Templates/SecondBrainStarter_Cursor/README-安裝到Cursor.md) (Traditional Chinese; the files it describes are already in place).

Match the language the user writes in. English in chat → English notes.

---

## Weekly Inbox ritual (~15 minutes)

Same time each week, process only `0-Inbox`, file each note with PARA, and log one line in that week’s Daily.

Steps: [WeeklyInboxRitual.md](7-Templates/WeeklyInboxRitual.md) (Traditional Chinese; the four questions work in any language).

---

## New computer

1. Install [Obsidian](https://obsidian.md/) and [Git](https://git-scm.com/).
2. `git clone` **your** repo; open the root as a vault.
3. Recheck Templates and Daily notes paths.
4. Optional: `git pull` before writing; `commit` / `push` when you pause.
5. **Privacy:** use a **Private** repo for sensitive notes. Do not push them back to this public template.

---

## iPhone

Phone and computer must share **the same files**. Pick one sync method:

| Method | Notes |
|--------|--------|
| **Obsidian Sync** | Official, paid, simplest. |
| **iCloud Drive** | Put the whole vault in one iCloud folder; open that folder on both devices. |
| **Git** | Working Copy or similar; higher friction. |

Do not heavily edit the same note on two devices before sync finishes.

---

## Long-term projects (optional three layers)

When you have a clear goal and want numbers or a dashboard:

| Layer | What goes here | Template |
|-------|----------------|----------|
| Plan | Goals, phases, principles | [LongTermProjectPlanTemplate.md](7-Templates/LongTermProjectPlanTemplate.md) |
| Dashboard | Daily grid, monthly snapshots | [LongTermProjectDashboardTemplate.md](7-Templates/LongTermProjectDashboardTemplate.md) |
| Daily | That day’s numbers and how it felt | `6-DailyNotes/YYYY-MM-DD.md` |

Keep conceptual notes in `5-Zettelkasten` and link from the project and Daily.

---

## Principles

- **No filing anxiety:** if unsure, use `0-Inbox`.
- **Zettelkasten:** one idea, your words; links matter more than folders.
- **Review weekly:** 15 minutes, see [WeeklyInboxRitual.md](7-Templates/WeeklyInboxRitual.md).

---

## About BB Studio

Soul partners × business experiments — turning warm trust into products that actually run.

BB Studio is co-named by two engineers — a workspace where we experiment with a "solo company × partnership" model.

We don't build bloated all-in-one platforms. We focus on real scenarios and ship small, deliverable tools and services where data stays in the user's hands.

### What we believe

- **Sell outcomes, not generic bots** — clients want their time back and their schedules handled, not another dashboard to learn.
- **Works offline too** — not every team can or should put their data in the cloud; we respect data sovereignty.

### How we work

We prefer: small pilot → interview-driven packaging → a runnable MVP — not selling a massive blueprint upfront.

Built with care — leave the complexity to the system, return calm to the user.
