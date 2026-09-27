# Install Cursor rules into a vault

This starter **already has** these files at the repo root. Copy them only if you are wiring a *different* vault.

```text
your-vault/
├── AGENTS.md
├── .cursor/
│   ├── rules/
│   │   └── second-brain-vault.mdc
│   └── skills/obsidian-markdown/
```

## Steps

1. Put `AGENTS.md` at the **vault root**.
2. Create `.cursor/rules/` and add `second-brain-vault.mdc` (`alwaysApply: true`).
3. Copy `.cursor/skills/obsidian-markdown/` from **this repository** (not from a personal vault).
4. Cursor → **Open Folder** on the vault root.

## Check

- Ask the agent to “create a test card in `5-Zettelkasten`” — it should use `[[wikilink]]` and the correct path.
- Ask it to commit — it should **ask first or refuse**, unless you explicitly requested a commit.

## User Rules vs project rules

Keep your Cursor **User Rules** if you want. Inside this project, `AGENTS.md` + `.mdc` win when they conflict with PARA.
