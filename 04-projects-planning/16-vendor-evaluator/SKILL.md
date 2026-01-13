# Vendor Evaluator

**Generate a vendor comparison matrix from requirements with justified scores and questions.**

---

## What This Does

Takes your requirements and vendor options, then generates a structured comparison matrix. Every score is justified, total cost of ownership is estimated, deal-breakers are flagged, and you get specific questions to ask each vendor before deciding.

| Output | What You Get |
|--------|--------------|
| vendor-comparison.md | Full comparison matrix with scores |
| vendor-profiles.md | Individual vendor assessments |
| questions-for-vendors.md | Due diligence questions |
| recommendation.md | Justified recommendation |

---

## Quick Start

### Option 1: Natural Language
> "Compare Slack, Teams, and Discord for team communication"

### Option 2: With Requirements
> "Evaluate CRM vendors against our requirements in input/"

### Option 3: Research Mode
> "Help me evaluate options for [category]"

---

## What I Need From You

### Required
- **Category/need**: What type of vendor are you evaluating?
- **Candidates**: Which vendors to compare (or ask for suggestions)

### Optional (Enhances Output)
- **Requirements**: Must-haves, nice-to-haves, deal-breakers
- **Budget**: For TCO evaluation
- **Team size**: For per-user pricing
- **Existing stack**: For integration evaluation
- **Vendor materials**: Sales decks, quotes, docs

---

## What I'll Pull Automatically

| Integration | What I Get | Fallback |
|-------------|-----------|----------|
| Web Search | Pricing, reviews, features | Use provided materials |
| Local Files | Vendor materials you provide | Web research only |

---

## Output Location

```
output/
├── vendor-comparison.md     # Comparison matrix
├── vendor-profiles.md       # Individual assessments
├── questions-for-vendors.md # Due diligence
└── recommendation.md        # Justified pick
```

---

## Examples

### Example 1: SaaS Tool Selection
**Input**: "Evaluate Airtable, Notion, and Coda for team knowledge base"

**Output**:
- Matrix: Features, pricing, integrations, learning curve
- Scores: Justified 1-5 ratings for each criterion
- TCO: 3-year cost including implementation
- Recommendation: With rationale

### Example 2: Service Provider
**Input**: Requirements doc + 3 vendor proposals

**Output**:
- Matrix: Comparing proposals against requirements
- Scores: Where each meets/misses requirements
- Questions: Clarifications needed per vendor
- Deal-breakers: Any disqualifiers identified

### Example 3: Technology Decision
**Input**: "Compare AWS, GCP, and Azure for our infrastructure"

**Output**:
- Matrix: Compute, storage, pricing, team expertise
- TCO: Estimated costs for your usage pattern
- Migration effort: If applicable
- Recommendation: Based on your context

---

## What I Won't Do

- **Won't hide weaknesses**: Every vendor's downsides surfaced
- **Won't guess at pricing**: Flag uncertain costs clearly
- **Won't ignore deal-breakers**: Disqualifiers are highlighted
- **Won't make arbitrary scores**: Every rating is justified
- **Won't recommend without caveat**: Confidence level stated

---

## Tips for Best Results

1. **Define requirements first**: Clear criteria enable fair comparison
2. **Include deal-breakers**: What would disqualify a vendor?
3. **Share your context**: Team size, budget, existing tools matter
4. **Provide vendor materials**: Proposals/quotes improve accuracy
5. **Note priorities**: "Security matters most" weights the evaluation

---

## Troubleshooting

### "Scores seem off"
Check justifications—if reasoning is wrong, scores will be. Provide correcting context.

### "Missing vendor"
Add to comparison: "Also include [vendor]"

### "TCO is inaccurate"
Provide your specific parameters: team size, usage patterns, contract length.

### "Need deeper analysis"
Ask for specific deep-dive: "Compare security features in detail"

---

*Part of The Unlikely Coder Cowork Skill Library*
