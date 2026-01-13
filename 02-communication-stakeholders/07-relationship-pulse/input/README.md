# Relationship Pulse — Input Folder

## What Goes Here

Configuration files and manual relationship data.

### Configuration Files

| File | Purpose |
|------|---------|
| `tier-config.md` | Define VIP, Key, Active, Casual tiers |
| `exclusions.md` | People/domains to exclude |
| `frequency-targets.md` | Custom contact frequency goals |

### Manual Data

| File | Purpose |
|------|---------|
| `contacts-import.csv` | Bulk import relationships |
| `notes/` | Manual notes about people |
| `interactions.md` | Log interactions not in email |

---

## Tier Configuration

```markdown
# tier-config.md

## VIP (Check weekly)
- sarah.chen@acme.com
- james.wilson@beta.com
- [Personal board members]

## Key Clients (Check bi-weekly)
- *@acme.com
- *@beta.com

## Mentors (Check monthly)
- mentor@email.com

## Custom: Investors (Check monthly)
- partner@vc.com
```

---

## Exclusions

```markdown
# exclusions.md

## Don't Track
- *@personal-domain.com
- family-member@email.com
- recruiters
- newsletters
```

---

## Manual Interaction Log

```markdown
# interactions.md

## 2024-01-15
- **Sarah Chen**: Lunch meeting, discussed Q1 priorities
- **James Wilson**: Phone call, caught up personally

## 2024-01-10
- **Mike Brown**: Conference encounter, exchanged cards
```

---

## Bulk Import Format

```csv
name,email,company,role,tier,notes
Sarah Chen,sarah@acme.com,Acme Corp,VP Product,VIP,Key client contact
James Wilson,james@beta.com,Beta Inc,CEO,Key,Met at conference
```
