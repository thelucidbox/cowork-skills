# Subscription Auditor

**Track, analyze, and optimize your subscription spending.**

---

## What This Does

Catalogs all your recurring subscriptions from bank statements, emails, or manual input. Calculates total spend, identifies forgotten subscriptions, and suggests optimizations to reduce costs.

| Output | What You Get |
|--------|--------------|
| subscriptions.md | Full catalog |
| cost-analysis.md | Spending breakdown |
| recommendations.md | Optimization suggestions |

---

## Quick Start

### Option 1: Natural Language
> "Audit all my subscriptions"

### Option 2: From Statements
> "Find subscriptions in my bank statements"

### Option 3: Optimization
> "How can I reduce my subscription costs?"

---

## What I Need From You

### Required
- **Subscription sources**: Statements, emails, or list

### Optional (Enhances Output)
- **Usage data**: How much you use each
- **Budget target**: Monthly spending goal
- **Priority services**: What matters most

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| Bank statements | Recurring charges | Manual input |
| Email receipts | Subscription confirmations | — |
| App stores | App subscriptions | Manual check |

---

## Output Location

```
output/
├── subscriptions.md
├── cost-analysis.md
├── recommendations.md
└── cancellation-scripts/
```

---

## Examples

### Example 1: Full Audit
**Input**: Bank statements + email receipts

**Output**:
- 35 active subscriptions found
- $450/month total spend
- 8 forgotten/unused services
- $120/month potential savings

### Example 2: Category Analysis
**Input**: Subscription list with usage

**Output**:
- Streaming: $65/month (3 services)
- Software: $150/month (8 tools)
- Memberships: $80/month (4 places)
- Overlap identified: 2 similar services

### Example 3: Optimization Plan
**Input**: "Reduce to $200/month"

**Output**:
- Essential services identified
- Cancellation priorities
- Downgrade options
- Annual vs monthly savings

---

## What I Won't Do

- **Won't cancel subscriptions**: Provides guidance only
- **Won't access accounts**: Works from exports
- **Won't judge spending**: Objective analysis

---

## Tips for Best Results

1. **Gather all statements**: Complete picture
2. **Note usage levels**: Honest assessment
3. **Review quarterly**: Subscriptions creep

---

*Part of The Unlikely Coder Cowork Skill Library*
