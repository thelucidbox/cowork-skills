# Energy Audit

**Analyze time and energy patterns to suggest schedule optimizations.**

---

## What This Does

Analyzes your calendar, notes, and self-reported energy to identify patterns. Shows where your time actually goes versus where you think it goes, correlates energy levels with activities, and suggests schedule optimizations.

| Output | What You Get |
|--------|--------------|
| energy-audit.md | Complete time and energy analysis |
| patterns.md | Identified patterns |
| optimization-suggestions.md | Schedule recommendations |

---

## Quick Start

### Option 1: Natural Language
> "Audit my energy for the last month"

### Option 2: With Calendar
> "Analyze where my time goes"

### Option 3: Focused Analysis
> "When am I most productive?"

---

## What I Need From You

### Required
- **Calendar access**: To see time allocation
- **Or**: Time log/notes about how you spend time

### Optional (Enhances Output)
- **Energy ratings**: Daily or activity-level energy notes
- **Productivity notes**: What felt effective vs. draining
- **Goals**: What you want to optimize for

---

## What I'll Pull Automatically

| Integration | What I Get | Fallback |
|-------------|-----------|----------|
| Calendar | Meeting times, categories | Manual time log |
| Notes | Energy mentions, productivity notes | Ask for input |

---

## Output Location

```
output/
├── energy-audit.md              # Full analysis
├── patterns.md                  # What I found
└── optimization-suggestions.md  # What to change
```

---

## Examples

### Example 1: Work Week Analysis
**Input**: Calendar + energy notes for one month

**Output**:
- Time allocation: 40% meetings, 30% focus, 20% admin, 10% breaks
- Energy pattern: Peaks Tuesday morning, dips Wednesday afternoon
- Insight: Back-to-back meetings correlate with low afternoon energy
- Suggestion: Buffer meetings, protect Tuesday mornings

### Example 2: Meeting Load
**Input**: Calendar access

**Output**:
- Meeting hours: 22 hours/week average
- Meeting-free days: 0 last month
- Longest focus block: 2 hours
- Suggestion: Institute no-meeting Thursdays

### Example 3: Energy Tracking
**Input**: Daily energy logs (1-10)

**Output**:
- Average: 6.2
- Best days: Tuesday (7.1), Thursday (6.8)
- Worst: Monday (5.4), Friday afternoon (4.2)
- Correlations: Sleep, exercise, meeting load

---

## What I Won't Do

- **Won't judge**: Descriptive, not prescriptive
- **Won't assume causes**: Correlation noted, causation you determine
- **Won't mandate changes**: Suggestions only
- **Won't track without your data**: Only analyze what you provide
- **Won't share data**: Analysis stays private

---

## Tips for Best Results

1. **Track energy simply**: Even "good/bad/meh" is useful
2. **Include calendar notes**: Meeting titles help categorize
3. **Note sleep and exercise**: Strong energy correlations
4. **Provide context**: "January was unusual because..."
5. **Analyze monthly**: Weekly is too noisy

---

## Troubleshooting

### "Patterns don't seem right"
More data helps. One week is noisy; one month shows patterns.

### "Calendar doesn't reflect reality"
Add notes about actual activities, not just scheduled ones.

### "Suggestions aren't practical"
Share constraints: "I can't move the Monday meeting."

### "Energy tracking is tedious"
Simplify: Just morning energy rating, or just after meetings.

---

*Part of The Unlikely Coder Cowork Skill Library*
