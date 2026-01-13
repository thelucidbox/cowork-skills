# Audience Splitter — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Email Integration | 2 min | Tone matching from your sent mail |
| No Integrations | 0 min | Full functionality with neutral tone |

---

## Option 1: With Email Integration

### What You'll Get
- Tone analysis from your previous communications
- Different tone profiles per audience type
- Matches your voice more accurately

### Setup (Gmail)
```
Settings → Integrations → Gmail → Connect
```

### Setup (Apple Mail)
```
System Settings → Privacy & Security → Mail → Enable
```

### How It's Used
- Searches your sent mail for similar communications
- Extracts your typical tone per audience type
- Applies your patterns to new versions

---

## Option 2: No Integrations (Standalone)

### What You'll Get
- Full audience splitting functionality
- Professional neutral tone defaults
- Can adjust based on your feedback

### How to Get Better Tone Matching
Option 1: Provide examples in input
```
input/
└── tone-samples/
    ├── exec-example.md
    ├── team-example.md
    └── client-example.md
```

Option 2: Describe preferences
> "I'm casual with team, formal with clients, extremely brief with execs"

---

## Default Audiences

| Audience | Default Tone | Default Depth |
|----------|--------------|---------------|
| Executive | Brief, outcome-focused | High-level only |
| Team | Direct, inclusive | Full context |
| Client | Professional, warm | Relevant details |
| Slack | Casual, scannable | Key points |
| Email | Formal, complete | Standard business |

### Customizing Defaults
Tell me your preferences:
> "My exec updates can be longer—CEO likes details"
> "Keep client communication very formal"

---

## Verifying Setup

### Test Command
> "Test audience splitter"

### Expected Result
```
✓ Ready to split content for audiences
✓ Tone source: [Email/Samples/Neutral default]
✓ Default audiences: exec, team, client, slack, email
```

---

## Audience Customization

### Adding Custom Audiences
> "Add versions for: board, investors, customer support"

### Removing Unused Audiences
> "Only generate exec and team versions"

### Per-Audience Rules
```
input/
└── audience-rules.md
```

Example:
```markdown
## Exec
- Max 3 sentences
- Lead with outcome
- Only escalate blockers

## Client
- Always positive framing
- Never mention internal challenges
- Include next steps
```

---

*Part of The Unlikely Coder Cowork Skill Library*
