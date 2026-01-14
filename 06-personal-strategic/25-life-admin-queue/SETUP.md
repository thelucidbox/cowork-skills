# Life Admin Queue — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Calendar | 2 min | Scheduling integration |
| No Integrations | 0 min | Full functionality |

---

## Optional: Calendar Integration

### Google Calendar
```
Settings → Integrations → Google Calendar → Connect
```

### Apple Calendar
```
System Settings → Privacy & Security → Calendar → Enable
```

### What You Get
- Automatic time block suggestions
- Conflict checking
- Direct calendar export

---

## No Setup Required

Works standalone:
- Creates .ics files for import
- Suggests schedule without checking conflicts
- Full queue management

---

## Verifying Setup

### Test Command
> "Test life admin queue"

### Expected Result
```
✓ Calendar: [Connected/Export mode]
✓ Ready to organize admin tasks
```

---

## Configuration

### Availability Windows
```
input/
└── admin-config.md
```

```markdown
## Admin Availability

### Phone Calls
- Best times: Tue/Thu 10am-12pm
- Can't call: Mondays (meetings)

### Online Tasks
- Any time
- Prefer: Evening wind-down

### In-Person
- Saturdays only
- Before noon

### Constraints
- Business hours: 9am-5pm
- Lunch calls OK
```

---

## Integration with Notes

If you capture admin items in daily notes:
```
input/
└── notes/
    └── admin-mentions.md
```

Extract admin items from across your notes.

---

*Part of Art of Fact Cowork Skill Library*
