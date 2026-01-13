# Research Synthesizer — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Web Search | 0 min | Current web research |
| PDF/Documents | 0 min | Document analysis |
| Both | 0 min | Combined synthesis |

---

## Fully Functional By Default

Research Synthesizer works immediately with:
- Web search for current information
- Document analysis for files you provide

---

## Web Search (Default On)

### What You'll Get
- Current information on topic
- Multiple source perspectives
- Recent developments
- Citation links

### Usage
> "Research [topic]"

Automatically searches for relevant sources.

---

## Document Analysis

### Supported Formats
- `.pdf` (research papers, reports)
- `.docx` (Word documents)
- `.txt` / `.md` (plain text)
- `.html` (web page saves)

### Usage
```
input/
├── report-1.pdf
├── whitepaper.pdf
└── article.docx
```

> "Synthesize the documents in input/"

---

## Verifying Setup

### Test Command
> "Test research synthesizer"

### Expected Result
```
✓ Web search: Available
✓ Document processing: Available
✓ Ready to synthesize research
```

---

## Research Configuration

### For Specialized Research
```
input/
└── research-config.md
```

```markdown
## Research Parameters

### Preferred Sources
- Industry reports from: Gartner, Forrester
- Technical from: Official documentation
- Avoid: Promotional content

### Date Preference
- Focus on: Last 12 months
- Or: Historical context included

### Citation Style
- Format: APA / MLA / Numbered
```

---

## Source Organization

### For Multiple Documents
```
input/
├── primary-sources/      # Key documents
│   └── [authoritative docs]
├── secondary-sources/    # Supporting
│   └── [additional docs]
└── ignore/               # In folder but skip
```

### Source Priority
Primary sources weighted more heavily in synthesis.

---

*Part of The Unlikely Coder Cowork Skill Library*
