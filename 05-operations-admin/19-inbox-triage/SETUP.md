# Inbox Triage — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Gmail | 3 min | Full inbox triage |
| Apple Mail | 3 min | Full inbox triage |

---

## Email Integration Required

Inbox Triage requires email access to function.

---

## Option 1: Gmail Setup

### Steps

1. **Connect Gmail**
   ```
   Settings → Integrations → Gmail → Connect
   ```

2. **Authorize Access**
   - Grant read access to inbox
   - Grant access to sent mail (for tone matching)

3. **Verify**
   > "Test inbox triage"

### Permissions Needed
- Read emails (for triage)
- Search emails (for filtering)
- Read sent mail (for tone matching)

---

## Option 2: Apple Mail Setup

### Steps

1. **Grant Mail Access**
   ```
   System Settings → Privacy & Security → Mail → Enable
   ```

2. **Verify**
   > "Test inbox triage"

### Note
May require Full Disk Access on some macOS versions.

---

## Verifying Setup

### Test Command
> "Test inbox triage"

### Expected Result
```
✓ Email: Connected
✓ Inbox access: Available
✓ Ready to triage
```

---

## Configuration

### VIP List
```
input/
└── triage-config.md
```

```markdown
## VIP Senders (Always Priority)
- boss@company.com
- client@acme.com
- *@important-domain.com

## Ignore (Never Priority)
- *@newsletter.com
- *@promotions.company.com
- noreply@*

## Priority Keywords
- urgent
- deadline
- asap
- by [today/tomorrow]
```

### Response Tone Examples
```
input/
└── response-examples/
    ├── formal-response.md
    └── casual-response.md
```

---

## Privacy Notes

- Email content accessed for triage only
- Not stored beyond session
- Response drafts are local files
- Full text never sent to external services

---

*Part of The Unlikely Coder Cowork Skill Library*
