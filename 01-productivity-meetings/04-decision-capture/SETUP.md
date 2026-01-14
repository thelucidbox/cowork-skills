# Decision Capture — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Any Integration | 0 min | Decision Capture is standalone |
| No Integrations | 0 min | Full functionality immediately |

---

## No Setup Required

Decision Capture works entirely through conversation. No integrations needed.

### Why Standalone?
- Decisions are context-specific
- Your input provides all needed information
- Frameworks work without external data
- Privacy preserved for sensitive decisions

---

## How It Works

### Input Methods

**Conversational**
Just describe your situation:
> "I'm deciding between three vendors for our CRM"

**Structured**
Provide components:
> "Situation: [X], Options: [A, B, C], Priorities: [speed, cost]"

**Exploratory**
Start uncertain:
> "I have a decision to make but I'm not even sure what my options are"

---

## Optional Enhancements

### Previous Decisions (For Pattern Matching)
If you want to reference past decisions:
```
input/
└── previous-decisions/
    ├── 2023-vendor-selection.md
    └── 2024-hiring-decision.md
```

This enables:
- "How did I decide last time?"
- Pattern recognition in your decision-making
- Consistency checking

### Decision Archive
Save outputs for future reference:
```
decisions/
├── 2024-01-analytics-platform.md
└── 2024-02-team-structure.md
```

---

## Verifying Setup

### Test Command
> "Test decision capture"

### Expected Result
```
✓ Decision Capture ready
✓ No integrations required
✓ Begin by describing your decision
```

---

## Decision Types Supported

| Type | Example |
|------|---------|
| Build vs. Buy | Technology selection |
| Hire vs. Outsource | Resourcing decisions |
| Go / No-Go | Launch decisions |
| A vs. B vs. C | Multiple options |
| Now vs. Later | Timing decisions |
| Career | Job offers, role changes |
| Strategic | Direction and priority |

---

## Privacy Note

Decision Capture processes everything locally in conversation. Sensitive decisions (compensation, personnel, strategy) are not stored or shared.

---

*Part of Art of Fact Cowork Skill Library*
