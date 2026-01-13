# Retro Runner — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Previous Retros | 2 min | Pattern detection |
| Calendar | 2 min | Time analysis |
| No Integrations | 0 min | Full retro generation |

---

## Primarily Standalone

Retro Runner creates complete retrospectives from your input. External data is optional enhancement.

---

## Optional: Pattern Tracking

### What You'll Get
- Recurring issues identified
- Experiment success tracking
- Trends over time

### Setup
Save previous retros:
```
input/
└── previous-retros/
    ├── sprint-45-retro.md
    ├── sprint-46-retro.md
    └── sprint-47-retro.md
```

---

## Optional: Calendar Integration

### What You'll Get
- Meeting load analysis
- Time allocation during sprint/project
- Interruption patterns

### Setup
```
Settings → Integrations → Calendar → Connect
```

---

## Verifying Setup

### Test Command
> "Test retro runner"

### Expected Result
```
✓ Ready to run retrospectives
✓ Previous retros: [N found/Not configured]
✓ Calendar: [Connected/Not connected]
```

---

## Retro Configuration

### Custom Format
```
input/
└── retro-config.md
```

```markdown
## Our Retro Format

### Sections
- What went well
- What could improve
- Action items

### Experiment Rules
- Must be specific
- Must be testable in 2 weeks
- Must have owner

### Skip
- Team dynamics section
```

---

## Team Input Collection

### Before Running
Collect input from team via:
- Anonymous survey
- Shared document
- Meeting notes

### Input Format
```markdown
# Team Input

## Sarah
- Went well: Clear sprint goal
- Could improve: Testing bottleneck

## Mike
- Went well: Good collaboration
- Could improve: Too many meetings
```

---

*Part of The Unlikely Coder Cowork Skill Library*
