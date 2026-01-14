# Network Mapper — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Full Integration | 5 min | Complete network analysis |
| Contacts Only | 2 min | Basic network map |
| Manual | 0 min | List-based analysis |

---

## Option 1: Full Integration

### Google Workspace
```
Settings → Integrations → Google Contacts → Connect
Settings → Integrations → Gmail → Connect
Settings → Integrations → Google Calendar → Connect
```

### Apple Ecosystem
```
System Settings → Privacy & Security → Contacts → Enable
System Settings → Privacy & Security → Mail → Enable
System Settings → Privacy & Security → Calendar → Enable
```

---

## Option 2: Contacts Only

Just connect contacts for basic mapping without communication history.

---

## Option 3: Manual

Provide a contact list:
```
input/
└── network.md
```

```markdown
## My Network

### Investors
- Jane Smith (VC Partner) - met 2022
- Bob Johnson (Angel) - introduced by Mike

### Mentors
- Sarah Chen (CTO) - monthly check-ins
```

---

## Verifying Setup

### Test Command
> "Test network mapper"

### Expected Result
```
✓ Contacts: Connected ([N] contacts)
✓ Email: Connected
✓ Calendar: Connected
✓ Ready to map network
```

---

## Relationship Tiers

Configure priority levels:
```
input/
└── network-config.md
```

```markdown
## Relationship Tiers

### Tier 1: Monthly Check-in
- Investors
- Key mentors
- Close collaborators

### Tier 2: Quarterly
- Industry contacts
- Former colleagues
- Advisors

### Tier 3: Semi-annual
- Conference connections
- Extended network
```

---

*Part of Art of Fact Cowork Skill Library*
