# Weekly Momentum Report — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Google Workspace | 5 min | Calendar analysis, email volume metrics |
| Apple Ecosystem | 5 min | Calendar.app, Mail volume |
| No Integrations | 0 min | Note-based analysis |

---

## Option 1: Google Workspace

### What You'll Get
- Meeting time analysis (hours in meetings)
- Focus time vs. fragmented time
- Email volume and thread counts
- Communication patterns

### Setup Steps

1. **Enable Google Calendar Access**
   ```
   Settings → Integrations → Google Calendar → Connect
   ```
   For meeting load analysis

2. **Enable Gmail Access** (Optional)
   ```
   Settings → Integrations → Gmail → Connect
   ```
   For communication volume metrics

### Permissions
- Calendar: Read-only
- Gmail: Read-only (counts only, not content)

---

## Option 2: Apple Ecosystem

### What You'll Get
- Calendar.app meeting analysis
- Mail.app volume metrics
- Local notes access

### Setup Steps

1. **Grant Calendar Access**
   ```
   System Settings → Privacy & Security → Calendar → Enable
   ```

2. **Grant Mail Access** (Optional)
   ```
   System Settings → Privacy & Security → Mail → Enable
   ```

---

## Option 3: No Integrations (Standalone Mode)

### What You'll Get
Full analysis based on your notes, including:
- Wins and blockers extraction
- Pattern detection from note content
- Priority recommendations

### What You Provide
- Notes from the week (any format)
- Optionally: calendar summary, energy ratings

### This Works Well If
- You keep detailed daily notes
- You prefer manual input
- You want quick setup

---

## Note Organization

### Recommended Structure
```
notes/
├── 2024/
│   ├── week-02/
│   │   ├── monday.md
│   │   ├── tuesday.md
│   │   └── ...
│   └── week-03/
│       └── ...
```

Or simply:
```
notes/
├── 2024-01-08.md
├── 2024-01-09.md
└── ...
```

### Supported Formats
- `.md` (Markdown)
- `.txt` (Plain text)
- `.docx` (Word)
- Obsidian vaults
- Apple Notes exports
- Notion exports

---

## Verifying Your Setup

### Test Command
> "Test weekly momentum integrations"

### Expected Results
```
✓ Notes folder: [path] (X files found)
✓ Calendar: Connected (or manual mode)
✓ Email: Connected (or skipped)
✓ Ready for weekly analysis
```

---

## Previous Report Continuity

### For Pattern Tracking
Save weekly reports in a consistent location:
```
reports/
├── 2024-week-01-momentum.md
├── 2024-week-02-momentum.md
└── ...
```

When generating new reports, I'll reference previous ones for:
- Recurring blockers (chronic issues)
- Trend identification
- Progress over time

---

## Energy Tracking Integration

### If You Track Energy
Include in daily notes:
```markdown
## Energy: 7/10
or
## Energy: High
or simply
Good energy today
```

### Compatible Apps
- Daylio exports
- Manual tracking in notes
- Apple Health (coming soon)

---

*Part of Art of Fact Cowork Skill Library*
