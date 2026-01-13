# Relationship Pulse — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Google Workspace | 5 min | Auto-tracking from email/calendar |
| Apple Ecosystem | 5 min | Mail/Calendar/Contacts integration |
| No Integrations | 0 min | Manual tracking mode |

---

## Option 1: Google Workspace

### What You'll Get
- Automatic interaction tracking from Gmail
- Meeting history from Google Calendar
- Contact info and notes from Google Contacts

### Setup Steps

1. **Enable Gmail Access**
   ```
   Settings → Integrations → Gmail → Connect
   ```
   Tracks who you communicate with and when

2. **Enable Google Calendar**
   ```
   Settings → Integrations → Google Calendar → Connect
   ```
   Tracks meetings and shared time

3. **Enable Google Contacts**
   ```
   Settings → Integrations → Google Contacts → Connect
   ```
   Pulls existing relationship notes

---

## Option 2: Apple Ecosystem

### What You'll Get
- Mail.app interaction tracking
- Calendar.app meeting history
- Contacts.app integration

### Setup Steps

1. **Grant Mail Access**
   ```
   System Settings → Privacy & Security → Mail → Enable
   ```

2. **Grant Calendar Access**
   ```
   System Settings → Privacy & Security → Calendar → Enable
   ```

3. **Grant Contacts Access**
   ```
   System Settings → Privacy & Security → Contacts → Enable
   ```

---

## Option 3: No Integrations (Manual Mode)

### What You'll Get
- Full relationship tracking
- Manually updated profiles
- All analysis features

### How It Works
Update profiles through conversation:
> "I met with Sarah Chen yesterday"
> "Add note to James Wilson: interested in our API product"

### Best For
- Privacy-conscious tracking
- Selective relationship management
- Supplementing automatic tracking

---

## Configuring Relationship Tiers

### Default Tiers

| Tier | Check Frequency | Alert After |
|------|-----------------|-------------|
| VIP | Weekly | 2 weeks |
| Key | Bi-weekly | 1 month |
| Active | Monthly | 2 months |
| Casual | Quarterly | 6 months |

### Customizing Tiers
```
input/
└── tier-config.md
```

```markdown
## My Relationship Tiers

### VIP (Alert after 1 week)
- [Name 1]
- [Name 2]

### Key Clients (Alert after 2 weeks)
- Acme Corp contacts
- Beta Inc contacts

### Personal Board (Alert after 1 month)
- [Mentor name]
- [Advisor name]
```

---

## Verifying Setup

### Test Command
> "Test relationship pulse integrations"

### Expected Result
```
✓ Email: Connected (tracking interactions)
✓ Calendar: Connected (tracking meetings)
✓ Contacts: Connected (X contacts available)
✓ Ready to analyze relationships
```

---

## Privacy Configuration

### Exclude Specific People
```
input/
└── exclusions.md
```

```markdown
## Don't Track
- personal-friend@email.com
- family members
```

### Separate Personal/Professional
> "Only track work email addresses"
> "Exclude @personal-domain.com"

---

*Part of The Unlikely Coder Cowork Skill Library*
