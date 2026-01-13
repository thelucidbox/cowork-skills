# Receipt Processor — Setup Guide

## Requirements

| Tool | Required |
|------|----------|
| OCR capability | Built-in |
| File access | Yes |

## Supported Formats

| Format | Quality |
|--------|---------|
| PDF | Best |
| PNG/JPG | Good |
| HEIC | Good |
| Email forward | Good |

---

## Verifying

> "Test receipt processor"

```
✓ OCR: Available
✓ File access: Ready
✓ Ready to process
```

---

## Configuration

```
input/
└── receipt-config.md
```

```markdown
## Settings
- Categories: Food, Transport, Supplies, Services
- Currency: USD
- Tax rate: 8.25%
- Business default: No
```

---

*Part of The Unlikely Coder Cowork Skill Library*
