# Retro Runner

**Transform project notes into a structured retrospective with patterns, experiments, and action items.**

---

## What This Does

Takes notes from a completed project or sprint and generates a structured retrospective. Focuses on systems rather than individuals, surfaces patterns across the work, and produces specific, testable experiments for improvement. Turns hindsight into foresight.

| Output | What You Get |
|--------|--------------|
| retrospective.md | Complete retro document |
| experiments.md | Testable improvement experiments |
| patterns.md | Recurring themes identified |
| team-dynamics.md | How team worked together |

---

## Quick Start

### Option 1: Natural Language
> "Run a retro on our Q4 product launch"

### Option 2: With Notes
> "Generate retrospective from the notes in input/"

### Option 3: Interactive
> "Help me facilitate a retro for my team"

---

## What I Need From You

### Required
- **Project/sprint context**: What are we reflecting on?
- **What happened**: Notes, outcomes, observations

### Optional (Enhances Output)
- **Team input**: What team members said went well/poorly
- **Metrics**: Did we hit goals? By how much?
- **Previous retros**: For pattern tracking

---

## What I'll Pull Automatically

| Integration | What I Get | Fallback |
|-------------|-----------|----------|
| Local Files | Project notes in input folder | Manual input |
| Calendar | Meeting load during period | Skip time analysis |
| Previous Retros | Recurring patterns | Single-retro view |

---

## Output Location

```
output/
├── retrospective.md    # Complete retro
├── experiments.md      # Things to try
├── patterns.md         # Recurring themes
└── team-dynamics.md    # Team observations
```

---

## Examples

### Example 1: Sprint Retrospective
**Input**: Sprint notes, stand-up summaries, team feedback

**Output**:
- What worked: Clear sprint goal, daily syncs
- What didn't: Last-minute requirements, testing bottleneck
- Experiments: "Try refinement on Wednesdays" (specific, testable)
- Patterns: Third sprint in a row with testing issues

### Example 2: Project Post-Mortem
**Input**: Project notes, timeline, outcome data

**Output**:
- What worked: Strong kickoff, good stakeholder comms
- What didn't: Scope creep in month 2, estimation off
- Experiments: "Document scope decisions weekly"
- Team dynamics: Who picked up slack, who was overloaded

### Example 3: Incident Retrospective
**Input**: Incident timeline, response notes

**Output**:
- What worked: Fast detection, clear escalation
- What didn't: Runbook outdated, communication gaps
- Experiments: "Monthly runbook review rotation"
- No blame: Focus on system improvements

---

## What I Won't Do

- **Won't blame individuals**: Focus on systems and processes
- **Won't accept vague experiments**: "Communicate better" → "Daily 5-min standup sync"
- **Won't skip uncomfortable truths**: Surface real issues
- **Won't assume same fixes work**: Check if past experiments were tried
- **Won't ignore success**: Celebrate and understand what worked

---

## Tips for Best Results

1. **Gather all perspectives**: Include input from entire team
2. **Note the emotions**: "Team was frustrated about X" is valid data
3. **Include metrics**: Quantify outcomes where possible
4. **Share previous retros**: Pattern detection needs history
5. **Be honest about failures**: Most learning comes from what didn't work

---

## Troubleshooting

### "Retro feels generic"
Provide more specific observations. "Things were slow" → "Deployments took 3 days instead of 3 hours."

### "Experiments aren't actionable"
Ask for more specific experiments: "Make each experiment a 2-week, testable change."

### "Team dynamics feels uncomfortable"
Can skip this section, or focus on roles/processes rather than individuals.

### "Don't see patterns"
Need multiple retros for pattern detection. Single retro gives snapshot, not trends.

---

*Part of The Unlikely Coder Cowork Skill Library*
