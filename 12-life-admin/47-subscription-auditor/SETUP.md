# Subscription Auditor — Setup Guide

## Requirements

| Tool | Required |
|------|----------|
| Statement exports | Recommended |
| Email access | Optional |

## Input Sources

| Source | What to Export |
|--------|----------------|
| Bank | PDF/CSV statements |
| Credit card | Transaction history |
| Email | Receipt emails |
| Manual | Known subscriptions |

---

## Verifying

> "Test subscription auditor"

```
✓ Statement parsing: Ready
✓ Pattern detection: Available
✓ Ready to audit
```

---

## Configuration

```
input/
└── audit-config.md
```

```markdown
## Settings
- Currency: USD
- Include trials: Yes
- Categorize by: Type
```

---

*Part of The Unlikely Coder Cowork Skill Library*
