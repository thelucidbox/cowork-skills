# Tax Prep Assembler — Setup Guide

## Requirements

| Tool | Required |
|------|----------|
| File access | Yes |
| Email access | Optional |

## Document Sources

| Source | Documents |
|--------|-----------|
| Employers | W-2, 1099 |
| Banks | 1099-INT, 1099-DIV |
| Brokers | 1099-B |
| Mortgage | 1098 |
| Receipts | Deductions |

---

## Verifying

> "Test tax prep assembler"

```
✓ File access: Available
✓ Document scanning: Ready
✓ Ready to assemble
```

---

## Configuration

```
input/
└── tax-config.md
```

```markdown
## Tax Profile
- Filing status: [status]
- Dependents: [number]
- Income types: W-2, 1099
- Deduction method: Itemized/Standard
```

---

*Part of The Unlikely Coder Cowork Skill Library*
