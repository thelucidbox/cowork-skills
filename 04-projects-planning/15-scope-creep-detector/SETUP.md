# Scope Creep Detector — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Document Files | 0 min | Full comparison |
| No Integrations | 0 min | Works standalone |

---

## No Setup Required

Scope Creep Detector works by comparing documents you provide. No external integrations needed.

---

## How It Works

### Provide Two States
1. **Original**: The agreed-upon scope (spec, SOW, charter)
2. **Current**: What's now expected (current requirements, feature list)

### Comparison Generated
- Line-by-line differences
- Categorized changes
- Impact assessment
- Renegotiation strategy

---

## Verifying Setup

### Test Command
> "Test scope creep detector"

### Expected Result
```
✓ Ready to detect scope creep
✓ Provide original spec and current state
```

---

## Input Options

### File-Based
```
input/
├── original-spec.md     # What was agreed
├── current-state.md     # What's now expected
└── change-log.md        # Optional: how we got here
```

### Conversational
> "Original scope: [paste original]"
> "Current state: [paste current]"

### Mixed
Provide original as file, describe current verbally.

---

## Configuration

### Impact Calculation
```
input/
└── project-context.md
```

```markdown
## Project Parameters

### Original Estimates
- Timeline: 8 weeks
- Budget: $50,000
- Team: 3 engineers

### Current Constraints
- Hard deadline: [Date or "Flexible"]
- Budget cap: [Amount or "Flexible"]
- Team: [Can add/cannot add]
```

---

*Part of The Unlikely Coder Cowork Skill Library*
