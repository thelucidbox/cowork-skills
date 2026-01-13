# Inbox Triage — Input Folder

## What Goes Here

Configuration files for triage preferences.

### Configuration

| File | Purpose |
|------|---------|
| `triage-config.md` | VIPs, ignore lists, keywords |
| `response-examples/` | Your email style examples |

---

## Triage Configuration

```markdown
# triage-config.md

## VIP Senders
- boss@company.com
- client@acme.com

## Always Archive
- *@newsletter.com
- noreply@*

## Priority Keywords
- urgent
- deadline
- asap

## Ignore Threads
- "[Newsletter]"
- "[Auto-reply]"
```

---

## Response Examples

```
input/
└── response-examples/
    ├── formal.md     # Example formal response
    └── casual.md     # Example casual response
```

Helps match your voice in response drafts.

---

## Without Config Files

Works with defaults:
- Standard urgency detection
- No VIP priority
- Generic response tone

Customize over time as you use the skill.
