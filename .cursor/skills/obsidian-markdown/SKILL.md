---
name: obsidian-markdown
description: >-
  Creates and edits Obsidian Flavored Markdown with wikilinks, embeds, callouts,
  YAML properties, comments, and Obsidian-specific syntax. Use when editing
  Markdown in this vault or when the user mentions Obsidian, wikilinks,
  callouts, frontmatter, tags, embeds, or OFM.
---

# Obsidian Flavored Markdown

Obsidian extends CommonMark and GFM. This skill covers **Obsidian-specific** syntax only; standard Markdown is assumed.

## Workflow: new or edited note

1. **Frontmatter** — See [references/PROPERTIES.md](references/PROPERTIES.md) for property types.
2. **Body** — Headings, lists, tasks, links as usual; add wikilinks/embeds/callouts per below.
3. **Internal links** — `[[Note]]` for vault notes; `[text](https://...)` for external URLs only.
4. **Embeds** — `![[...]]`; details in [references/EMBEDS.md](references/EMBEDS.md).
5. **Callouts** — `> [!type]`; full list in [references/CALLOUTS.md](references/CALLOUTS.md).

## Wikilinks

```markdown
[[Note Name]]
[[Note Name|Display Text]]
[[Note Name#Heading]]
[[Note Name#^block-id]]
[[#Heading in same note]]
```

Block ID on a paragraph:

```markdown
Paragraph text. ^my-id
```

For quotes/lists, put `^id` on its own line after the block.

## Embeds (summary)

```markdown
![[Note Name]]
![[Note Name#Heading]]
![[image.png|300]]
![[doc.pdf#page=3]]
```

See [references/EMBEDS.md](references/EMBEDS.md).

## Callouts (summary)

```markdown
> [!note]
> Body.

> [!tip] Title
> Body.

> [!faq]- Folded default
> Body.
```

See [references/CALLOUTS.md](references/CALLOUTS.md).

## Properties (frontmatter)

```yaml
---
title: My Note
date: 2024-01-15
tags:
  - project
aliases:
  - Other Name
cssclasses:
  - my-class
---
```

See [references/PROPERTIES.md](references/PROPERTIES.md).

## Tags (inline)

```markdown
#tag
#parent/child
```

## Comments

```markdown
Visible %%hidden%% visible.

%%
Block hidden in reading view.
%%
```

## Other OFM

- Highlight: `==text==`
- Math: `$inline$` and `$$ block $$`
- Mermaid: fenced `mermaid` code block; optional `class Node internal-link;` for note links

## Official docs

- [Obsidian Flavored Markdown](https://help.obsidian.md/obsidian-flavored-markdown)
- [Internal links](https://help.obsidian.md/links)
- [Embeds](https://help.obsidian.md/embeds)
- [Callouts](https://help.obsidian.md/callouts)
- [Properties](https://help.obsidian.md/properties)
