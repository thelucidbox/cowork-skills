# Contract Scanner

**Extract key terms, red flags, and questions from contracts—NOT legal advice.**

---

## What This Does

Takes a contract document and extracts key terms, identifies potential red flags, and generates questions for legal review. Creates a summary for quick understanding and calendar reminders for critical dates. This is NOT legal advice—always have a lawyer review.

| Output | What You Get |
|--------|--------------|
| contract-summary.md | Key terms extracted |
| red-flags.md | Potential concerns flagged |
| questions-for-legal.md | Questions to ask your lawyer |
| calendar-entry.ics | Important dates |

---

## Quick Start

### Option 1: Natural Language
> "Scan this vendor contract for key terms"

### Option 2: With File
> "Analyze the contract in input/"

### Option 3: Specific Focus
> "What are the termination clauses in this agreement?"

---

## What I Need From You

### Required
- **Contract document**: PDF, Word doc, or text

### Optional (Enhances Output)
- **Contract type**: SaaS, employment, NDA, vendor, etc.
- **Your role**: Are you the buyer or seller?
- **Concerns**: Specific areas to focus on
- **Comparison**: Other contracts to compare terms

---

## What I'll Pull Automatically

| Integration | What I Get | Fallback |
|-------------|-----------|----------|
| Local Files | Contract from input folder | Paste text |
| Calendar | Add important dates | Export .ics file |

---

## Output Location

```
output/
├── contract-summary.md      # Key terms
├── red-flags.md             # Potential concerns
├── questions-for-legal.md   # For your lawyer
└── calendar-entry.ics       # Important dates
```

---

## Examples

### Example 1: SaaS Agreement
**Input**: Software subscription agreement PDF

**Output**:
- Summary: Term, pricing, data ownership, SLA
- Red flags: Auto-renewal (90 days notice), unlimited liability
- Questions: "What happens to data on termination?"
- Calendar: Contract end date, renewal notice deadline

### Example 2: Vendor Contract
**Input**: Professional services agreement

**Output**:
- Summary: Scope, fees, IP ownership, confidentiality
- Red flags: Broad indemnification clause
- Questions: "Should we cap indemnification?"
- Calendar: Payment milestones, deliverable dates

### Example 3: NDA Review
**Input**: Mutual NDA

**Output**:
- Summary: Parties, definition of confidential, term
- Red flags: Very broad definition, long term (5 years)
- Questions: "Is 5-year term standard for our industry?"

---

## What I Won't Do

- **Won't provide legal advice**: This is extraction, not counsel
- **Won't guarantee completeness**: May miss nuances
- **Won't replace lawyer review**: Always get professional advice
- **Won't sign for you**: Information only
- **Won't interpret complex terms**: Flag for expert review

---

## DISCLAIMER

**This skill provides document analysis, NOT legal advice.** Always have contracts reviewed by a qualified attorney before signing. Red flags identified are potential concerns, not definitive legal problems. Questions generated are starting points for discussion with your lawyer.

---

## Tips for Best Results

1. **Full document**: Partial contracts miss context
2. **Note your role**: Buyer vs. seller changes what matters
3. **Share concerns**: "I'm worried about liability" focuses analysis
4. **Include attachments**: Schedules and exhibits matter
5. **Ask your lawyer**: Use outputs to prepare for legal review

---

## Troubleshooting

### "Missing sections"
Some contracts reference external documents. Note what's missing.

### "Red flags seem minor"
May be standard terms. Discuss with lawyer to assess.

### "Need deeper analysis"
Ask for specific section review: "Analyze Section 7 in detail."

### "Different contract type"
Specify: "This is an employment contract, not vendor agreement."

---

*Part of The Unlikely Coder Cowork Skill Library*
