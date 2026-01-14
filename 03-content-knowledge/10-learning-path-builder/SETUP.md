# Learning Path Builder — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Web Search | 0 min | Current resources, free courses |
| No Integrations | 0 min | Curated classic resources |

---

## Primarily Standalone

Learning Path Builder works through conversation. Main value comes from web search for current resources.

---

## Web Search (Default)

### What You'll Get
- Current best free resources
- Up-to-date course recommendations
- Recent tutorials and guides
- Active community resources

### How It Works
Automatically searches for:
- "[Topic] tutorial [year]"
- "[Topic] free course"
- "[Topic] learning path"
- "[Topic] beginner resources"

---

## No Web Search Mode

### What You'll Get
- Time-tested classic resources
- Fundamental curriculum structure
- General learning principles
- Evergreen recommendations

### When This Is Better
- Stable topics (math, fundamentals)
- You prefer curated over current
- Privacy preference

---

## Verifying Setup

### Test Command
> "Test learning path builder"

### Expected Result
```
✓ Ready to build learning paths
✓ Web search: Available
✓ Tell me what you want to learn
```

---

## Customization Options

### Learning Profile (Optional)
```
input/
└── learning-profile.md
```

```markdown
## My Learning Preferences

### Time
- Available: 5 hours/week
- Best time: Mornings

### Style
- Prefer: Video tutorials
- Avoid: Long textbooks

### Constraints
- Budget: Free only
- Or: Up to $50/month

### Current Skills
- Programming: Intermediate Python
- Design: None
```

### Previous Learning Paths
Save completed paths for reference:
```
input/
└── completed/
    ├── python-basics-completed.md
    └── sql-fundamentals-completed.md
```

---

## Resource Preferences

### Tell Me Your Preferences
> "I prefer YouTube tutorials over reading"
> "Only free resources please"
> "Include a paid course if it's really worth it"

### Platform Preferences
> "I have LinkedIn Learning through work"
> "I already have a Coursera subscription"
> "Prefer O'Reilly books"

---

*Part of Art of Fact Cowork Skill Library*
