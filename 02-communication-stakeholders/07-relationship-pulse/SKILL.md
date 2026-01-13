# Relationship Pulse

**Extract insights from interactions to maintain relationship profiles and flag neglected connections.**

---

## What This Does

Analyzes your communications—emails, calendar, notes—to build and maintain relationship profiles. Tracks interaction frequency, surfaces insights about each person, and flags relationships that may need attention. Over time, accumulates knowledge to make every interaction more informed.

| Output | What You Get |
|--------|--------------|
| profiles/{name}.md | Individual relationship profiles |
| relationship-health.md | Dashboard of all tracked relationships |
| reconnection-drafts/ | Ready-to-send rekindle messages |
| insights.md | Patterns across your network |

---

## Quick Start

### Option 1: Natural Language
> "Check on my relationship with Sarah Chen"

### Option 2: Full Network
> "Run relationship pulse on my network"

### Option 3: Specific Check
> "Who haven't I talked to in 3 months?"

---

## What I Need From You

### Required
- **Communication access**: Email/calendar for automatic tracking, or manual updates

### Optional (Enhances Output)
- **Priority contacts**: Who matters most (VIPs, key clients, close friends)
- **Relationship goals**: What you're trying to achieve with whom
- **Notes**: Your observations about people
- **Frequency targets**: How often you want to connect with different tiers

---

## What I'll Pull Automatically

| Integration | What I Get | Fallback |
|-------------|-----------|----------|
| Email | Communication frequency, topics discussed | Manual tracking |
| Calendar | Meeting history, scheduled time together | Manual tracking |
| Contacts | Basic info, notes you've saved | Build from scratch |

---

## Output Location

```
output/
├── profiles/
│   ├── sarah-chen.md
│   ├── james-wilson.md
│   └── ...
├── relationship-health.md
├── reconnection-drafts/
│   └── [name]-reconnect.md
└── insights.md
```

---

## Examples

### Example 1: Client Relationship Check
**Input**: "How's my relationship with Acme Corp contacts?"

**Output**:
- Profiles for each Acme contact
- Last interaction dates
- Health status: "Strong with Sarah, declining with Mike"
- Reconnection draft for Mike

### Example 2: Network Health Scan
**Input**: "Run relationship pulse"

**Output**:
- Dashboard: 45 active relationships tracked
- Healthy (contacted <30 days): 28
- Needs attention (30-90 days): 12
- At risk (>90 days): 5
- Reconnection drafts for at-risk relationships

### Example 3: Pre-Meeting Context
**Input**: "What do I know about James Wilson before our call?"

**Output**:
- Profile: Role, company, history with you
- Last 5 interactions summarized
- Topics discussed, preferences noted
- Conversation starters based on history

---

## What I Won't Do

- **Won't track without your data**: Only analyzes what you provide/connect
- **Won't contact people**: Drafts reconnection, you send
- **Won't share relationship data**: Profiles stay private
- **Won't judge relationships**: Reports status, you decide importance
- **Won't forget boundaries**: Respect professional/personal separation

---

## Tips for Best Results

1. **Tag VIP contacts**: I'll alert you sooner when they're neglected
2. **Add notes after interactions**: "Sarah mentioned new baby" enriches profiles
3. **Set frequency targets**: "Talk to investors monthly" creates useful alerts
4. **Review weekly**: Quick scan catches relationships before they go cold
5. **Include personal network**: Optional but valuable for holistic view

---

## Troubleshooting

### "Profile is thin"
More interactions = richer profile. Also try:
- Adding notes manually
- Connecting calendar for meeting history
- Reviewing email thread for insights

### "Missing people"
- Check email/contacts integration
- Add manually: "Add [name] to relationship tracking"
- They may not be in your digital trail

### "Wrong interaction dates"
Email dates may not match actual conversations (especially if discussed in person). Manually note: "Actually spoke with [name] on [date]."

### "Don't want to track everyone"
Specify: "Only track professional relationships" or "Exclude personal contacts"

---

*Part of The Unlikely Coder Cowork Skill Library*
