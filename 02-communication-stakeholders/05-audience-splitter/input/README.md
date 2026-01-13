# Audience Splitter — Input Folder

## What Goes Here

Your source content and optional customization files.

### Primary Input

| File | Purpose |
|------|---------|
| `update.md` | The content to split into versions |
| `announcement.txt` | Or any named source file |

### Optional Customization

| File | Purpose |
|------|---------|
| `audience-rules.md` | Per-audience formatting rules |
| `tone-samples/` | Example communications per audience |
| `sensitive-items.md` | What to exclude from certain versions |

---

## Folder Structure

```
input/
├── update.md              # Your source content
├── audience-rules.md      # Optional: custom rules
├── sensitive-items.md     # Optional: exclusions
└── tone-samples/          # Optional: style examples
    ├── exec-example.md
    ├── team-example.md
    └── client-example.md
```

---

## Tone Samples Format

If providing tone examples:

```markdown
# Exec Example

Subject: Q3 Update

Revenue up 12%. Customer acquisition on track.
Need decision on Q4 hiring by Friday.

—[Name]
```

```markdown
# Team Example

Hey team!

Quick update on where we landed with the Q3 numbers...
[your typical team communication style]
```

---

## Without Input Files

Works fine conversationally:
> "Split this for exec and client: [paste your content]"
