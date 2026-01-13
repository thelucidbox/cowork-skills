# Email Digest Generator — Setup Guide

## Requirements

| Tool | Required |
|------|----------|
| Email export/access | Yes |

## Input Methods

| Method | How |
|--------|-----|
| Export | .eml, .mbox files |
| Copy/paste | Email text |
| Forward | To processing address |

---

## Verifying

> "Test email digest generator"

```
✓ Email parsing: Ready
✓ Summarization: Available
✓ Ready to digest
```

---

## Configuration

```
input/
└── digest-config.md
```

```markdown
## Settings
- VIP senders: [list]
- Priority topics: [list]
- Ignore patterns: [newsletters, automated]
```

---

*Part of The Unlikely Coder Cowork Skill Library*
