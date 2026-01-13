# Vendor Evaluator — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Web Search | 0 min | Current vendor info |
| Vendor Materials | 0 min | Proposal analysis |
| Both | 0 min | Comprehensive evaluation |

---

## Fully Functional By Default

Vendor Evaluator uses web search for current information about vendors. No setup required.

---

## Web Research (Default On)

### What You'll Get
- Current pricing information
- Feature comparisons
- Recent reviews and feedback
- Integration capabilities

---

## Adding Vendor Materials

### For Better Analysis
```
input/
├── requirements.md           # Your criteria
├── vendor-proposals/
│   ├── vendor-a-proposal.pdf
│   ├── vendor-b-quote.docx
│   └── vendor-c-overview.md
```

### Supported Formats
- `.pdf` (proposals, sales decks)
- `.docx` (quotes, SOWs)
- `.md` / `.txt` (notes)
- `.xlsx` (pricing spreadsheets)

---

## Verifying Setup

### Test Command
> "Test vendor evaluator"

### Expected Result
```
✓ Web search: Available
✓ Document analysis: Available
✓ Ready to evaluate vendors
```

---

## Configuration

### Requirements Template
```
input/
└── requirements.md
```

```markdown
# Vendor Requirements

## Must-Have
- [ ] [Requirement 1]
- [ ] [Requirement 2]

## Nice-to-Have
- [ ] [Requirement 3]
- [ ] [Requirement 4]

## Deal-Breakers
- [Disqualifier 1]
- [Disqualifier 2]

## Budget
- Maximum: $X/year
- Preferred: $Y/year

## Team Context
- Size: [N] users
- Technical level: [High/Medium/Low]
- Existing tools: [List]
```

---

## Scoring Customization

### Default Weights
- Must-haves: 5x weight
- Nice-to-haves: 2x weight
- Deal-breakers: Disqualifying

### Custom Weights
> "Weight security 3x and price 2x in the evaluation"

---

*Part of The Unlikely Coder Cowork Skill Library*
