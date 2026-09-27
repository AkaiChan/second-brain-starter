# Obsidian callouts

Syntax:

```markdown
> [!type]
> Content (Markdown inside).

> [!type] Optional title
> Content.

> [!type]+ Expanded by default
> > Nested callout supported.
```

Fold modifiers:

- `+` start expanded  
- `-` start collapsed  

## Common types

`note`, `abstract`, `info`, `todo`, `tip`, `success`, `question`, `warning`, `failure`, `danger`, `bug`, `example`, `quote`

Aliases exist (e.g. `hint` → `tip`, `caution` → `warning`); see official list.

## Nesting

Indent inner `>` under outer callout.

## Custom types (themes/CSS)

Community themes may add types via CSS; stick to built-in names for portability unless your theme documents extras.

## More detail

[Callouts - Obsidian Help](https://help.obsidian.md/callouts)
