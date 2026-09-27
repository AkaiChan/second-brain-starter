# Obsidian properties (YAML frontmatter)

Properties live between `---` lines at the file start. They power search, templates, and plugins.

## Common built-in keys

| Key | Role |
|-----|------|
| `tags` | List or inline-style tags; searchable |
| `aliases` | Alternate titles for link autocomplete |
| `cssclasses` | CSS class names for Reading view styling |

## Types (YAML)

- **Text** — string
- **Number** — integer or float
- **Checkbox** — `true` / `false`
- **Date** — `YYYY-MM-DD`
- **Date & time** — ISO-style string
- **List** — YAML list

Custom keys are allowed; consistency across your vault helps.

## Tags in frontmatter

```yaml
tags:
  - literature
  - book
```

Rules for tag characters match inline tags (letters, numbers not first, `_`, `-`, `/`).

## More detail

[Properties - Obsidian Help](https://help.obsidian.md/properties)
