# Cursor Agent — Obsidian Second Brain (PARA + Zettel) Template

This repository is an **Obsidian vault template**, not an application. The agent’s job is to **create/edit Markdown notes, keep the PARA structure, and help the user organize knowledge**.

Authoritative docs: root **`README.md`** (Chinese + English summary) and **`README.en.md`**.

---

## What this project is

| Item | Notes |
|------|--------|
| **Type** | Obsidian vault (PARA + Zettelkasten + Daily Notes) |
| **Audience** | Anyone who opens the folder in Cursor and wants AI help writing notes |
| **Version control** | Git (optional GitHub); notes are the product |

---

## Directories (standard PARA — do not rename)

| Path | Purpose |
|------|---------|
| `0-Inbox/` | Staging; empty **weekly** (`7-Templates/WeeklyInboxRitual.md`) |
| `1-Projects/` | Goals that can be finished |
| `2-Areas/` | Ongoing responsibilities, no single deadline |
| `3-Resources/` | Topic references, reading / assets |
| `4-Archives/` | Finished projects or items no longer in focus |
| `5-Zettelkasten/` | Permanent notes: **one idea each**, in the user’s own words |
| `6-DailyNotes/` | `YYYY-MM-DD.md` daily notes |
| `7-Templates/` | Templates and rituals (Daily, Inbox, long-term projects, …) |

**Unsure** → `0-Inbox`, or ask the user.

---

## Writing notes (Obsidian Flavored Markdown)

1. **Internal links** use wikilinks: `[[Note]]`, `[[Note#Heading]]`. External: `[text](https://...)`.
2. **Frontmatter** (recommended): `title`, `date`, `tags`; projects may add `status`, `type`.
3. **Callouts**: `> [!note]`, `> [!tip]`, etc.
4. **Zettel**: do not paste whole articles; one idea per note; `[[link]]` related cards.
5. **Daily**: always `6-DailyNotes/YYYY-MM-DD.md`; may link `1-Projects` and `5-Zettelkasten`.
6. If **`.cursor/skills/obsidian-markdown/`** exists, **read that SKILL** before editing vault Markdown.

---

## Long-term projects (three layers, optional)

| Layer | Where | Template |
|-------|--------|----------|
| Plan | `1-Projects/…` | `7-Templates/LongTermProjectPlanTemplate.md` |
| Dashboard | Same project folder | `7-Templates/LongTermProjectDashboardTemplate.md` |
| Daily | `6-DailyNotes/` | `7-Templates/DailyNoteTemplate.md` |

---

## Agent rules

### Must

- Understand **README** and intent first; **minimal diff**; leave unrelated files alone.
- Put new notes in the **correct PARA folder**; clear filenames; avoid odd characters.
- **Match the user’s language:** Traditional Chinese in chat → Traditional Chinese notes and replies. English in chat → English notes and replies. Do not switch language unless asked.
- **Privacy:** do not invent personal data; do not suggest pushing sensitive notes to a public repo (including this template).

### Git

- `git commit` / `push` **only when the user explicitly asks**.
- Do **not** change `git config`; do not force-push.
- Prefer not to commit `.obsidian/workspace.json` or plugin `data.json` (see `.gitignore`).

### Do not

- Treat this template as an app repo (no `package.json` / framework scaffold unless asked).
- Delete top-level PARA folders or wipe existing notes.
- Commit or push without permission.
- Specialize this template into one person’s private workflow (e.g. empty `2-Areas`, Cursor-only). Keep the **standard PARA teaching edition**.

---

## Common tasks

| User says | Agent does |
|-----------|------------|
| Today X happened | Update or create today’s Daily; add wikilinks as needed |
| Keep this idea | Inbox, Zettel, or Project (deadline vs action) |
| Process Inbox | WeeklyInboxRitual four questions; move files; one next step |
| New project | Hub in `1-Projects/` from `ProjectTemplate` or LongTerm templates |
| New computer / clone | Point to README “new computer” / iPhone sections |

---

## Obsidian settings (user must click)

- **Templates** → folder `7-Templates`
- **Daily notes** → new files `6-DailyNotes`, template `7-Templates/DailyNoteTemplate.md`

The agent can remind; it cannot click the Obsidian UI.

---

## Later evolution (not this template’s default)

If asked how a vault grows after months of use: people sometimes keep long themes as `1-Projects` hubs and write richer Dailies. That is **personalization** — do not apply it to this starter unless asked.
