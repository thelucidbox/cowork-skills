# Expense Processor — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Image Files | 0 min | Full OCR processing |
| No Integrations | 0 min | Works immediately |

---

## No Setup Required

Expense Processor uses built-in OCR capabilities to read receipt images.

---

## Supported Image Formats

| Format | Quality |
|--------|---------|
| `.jpg` / `.jpeg` | Best |
| `.png` | Good |
| `.heic` | Good (Apple) |
| `.pdf` | Works (if image-based) |

---

## Verifying Setup

### Test Command
> "Test expense processor"

### Expected Result
```
✓ OCR: Available
✓ Spreadsheet generation: Available
✓ Drop receipts in input/ folder
```

---

## Configuration Options

### Expense Policy
```
input/
└── expense-policy.md
```

```markdown
## Expense Policy

### Categories
- Meals: <$75/person
- Travel: Requires pre-approval >$500
- Supplies: <$100 without approval

### Flagging Rules
- Flag: Amounts >$100
- Flag: Weekend expenses
- Flag: Alcohol purchases

### Project Codes
- PROJ-001: Client A
- PROJ-002: Internal
- ADMIN: General
```

### Category Defaults
If you always categorize certain vendors:
```markdown
## Vendor Categories

- Uber: Transport
- Lyft: Transport
- Starbucks: Meals
- Amazon: Supplies
```

---

## Receipt Photo Tips

### Good Photo
- Flat surface
- Even lighting
- Full receipt visible
- In focus

### Common Problems
- Crumpled receipt: Flatten before photo
- Faded thermal: Photograph soon after purchase
- Long receipts: Multiple overlapping photos OK

---

*Part of The Unlikely Coder Cowork Skill Library*
