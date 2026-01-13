# Knowledge Capture — Input Folder

## What Goes Here

Context files and KB configuration.

### Configuration

| File | Purpose |
|------|---------|
| `kb-config.md` | KB location and settings |
| `kb-template.md` | Your article format |
| `tags.md` | Your tag taxonomy |

### Problem Context

| File | Purpose |
|------|---------|
| `troubleshooting-notes.md` | Your raw notes |
| `error-logs.txt` | Relevant error messages |
| `solution-steps.md` | What you did |

---

## Folder Structure

```
input/
├── kb-config.md         # Optional: KB settings
├── kb-template.md       # Optional: Your format
└── context/
    └── [problem notes]
```

---

## Without Input Files

Works perfectly through conversation:
> "Capture this: I fixed [problem] by [solution]"

The conversation captures all needed context.

---

## Template Example

If you want articles to match your format:

```markdown
# kb-template.md

## Our KB Format

### Title
[Problem as question]

### Environment
[Where this applies]

### Problem
[What's wrong]

### Solution
[How to fix]

### Notes
[Additional context]
```
