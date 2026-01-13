# Knowledge Capture — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Existing KB | 2 min | Related article linking |
| No Integrations | 0 min | Full standalone functionality |

---

## Primarily Standalone

Knowledge Capture creates complete articles without external dependencies. The value is in the structured capture process.

---

## Optional: Link to Existing KB

### What You'll Get
- Automatic related article suggestions
- Consistent tagging with existing KB
- Cross-reference generation

### Setup
Point to your knowledge base location:
```
input/
└── kb-config.md
```

```markdown
## KB Configuration

### Location
- Path: /path/to/knowledge-base/
- Or URL: https://notion.so/workspace/kb

### Categories
- Technical
- Process
- Tools
- Onboarding

### Tag Taxonomy
- Use existing tags from: /kb/tags.md
```

---

## No Setup Required

### How It Works
1. Describe the problem and solution
2. Receive structured KB article
3. Add to your knowledge base manually

### Works With Any KB
- Notion
- Confluence
- GitBook
- GitHub wiki
- Markdown files
- Any text system

---

## Verifying Setup

### Test Command
> "Test knowledge capture"

### Expected Result
```
✓ Ready to capture knowledge
✓ KB location: [Configured/Not configured]
✓ Describe a problem you solved
```

---

## KB Format Customization

### Use Your Template
```
input/
└── kb-template.md
```

Provide your organization's KB format and articles will match.

### Default Format Includes
- Problem statement
- Symptoms
- Root cause
- Solution (step-by-step)
- Gotchas
- Tags
- Related articles

---

## Building a KB Over Time

### Recommended Structure
```
knowledge-base/
├── technical/
│   ├── api-timeout-fix.md
│   └── npm-cache-clear.md
├── process/
│   └── expense-approval-workflow.md
└── index.md
```

### Making Articles Findable
- Include error messages verbatim
- Use common search terms
- Tag consistently
- Cross-reference related articles

---

*Part of The Unlikely Coder Cowork Skill Library*
