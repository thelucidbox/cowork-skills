# Contract Scanner — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| PDF/Documents | 0 min | Full contract analysis |
| Calendar | 2 min | Auto-add important dates |
| No Integrations | 0 min | Works immediately |

---

## No Setup Required

Contract Scanner reads PDFs and documents without additional setup.

---

## Supported Formats

| Format | Support |
|--------|---------|
| `.pdf` | Full support |
| `.docx` | Full support |
| `.doc` | Supported |
| `.txt` / `.md` | Full support |

---

## Optional: Calendar Integration

### What You'll Get
- Important dates added to calendar
- Renewal notice reminders
- Expiration warnings

### Setup (Google)
```
Settings → Integrations → Google Calendar → Connect
```

### Setup (Apple)
```
System Settings → Privacy & Security → Calendar → Enable
```

### Alternative
Export `.ics` file and manually import.

---

## Verifying Setup

### Test Command
> "Test contract scanner"

### Expected Result
```
✓ PDF processing: Available
✓ Document analysis: Available
✓ Calendar: [Connected/Export mode]
✓ Drop contract in input/ folder
```

---

## Configuration

### Focus Areas by Contract Type
```
input/
└── scan-config.md
```

```markdown
## Contract Scanning Preferences

### Our Role
- Usually: Buyer / Customer

### Priority Concerns
- Liability caps
- Data ownership
- Termination rights
- Auto-renewal terms

### Standard Terms (Skip Flagging)
- [Terms we accept as standard]
```

---

## Legal Disclaimer Setup

Outputs always include:
```
DISCLAIMER: This analysis is not legal advice.
Consult a qualified attorney before signing.
```

Cannot be disabled—legal review is always required.

---

*Part of Art of Fact Cowork Skill Library*
