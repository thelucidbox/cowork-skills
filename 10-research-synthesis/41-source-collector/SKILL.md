# Source Collector

**Gather, organize, and cite sources for research projects systematically.**

---

## What This Does

Collects sources from various inputs (URLs, PDFs, notes), extracts key information, generates proper citations, and creates organized research bibliographies with annotations and relevance ratings.

| Output | What You Get |
|--------|--------------|
| sources/ | Collected materials |
| bibliography.md | Formatted citations |
| source-notes.md | Annotated summaries |

---

## Quick Start

### Option 1: Natural Language
> "Collect and organize my sources on climate change"

### Option 2: From URLs
> "Add these articles to my research sources"

### Option 3: Build Bibliography
> "Create a bibliography from my collected sources"

---

## What I Need From You

### Required
- **Sources**: URLs, files, or references

### Optional (Enhances Output)
- **Citation style**: APA, MLA, Chicago, etc.
- **Research topic**: For relevance assessment
- **Annotation needs**: Summary requirements

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| URLs | Article metadata | Manual entry |
| PDFs | Title, author, date | Filename |
| DOIs | Full citation data | Partial info |

---

## Output Location

```
output/
├── sources/
│   ├── articles/
│   ├── books/
│   └── other/
├── bibliography.md
└── source-notes.md
```

---

## Examples

### Example 1: Research Paper Sources
**Input**: 25 URLs and 10 PDFs

**Output**:
- All sources cataloged
- APA citations generated
- Annotated bibliography
- Relevance rankings

### Example 2: Literature Review
**Input**: Academic sources on topic

**Output**:
- Categorized by theme
- Key findings extracted
- Citation network mapped
- Gaps identified

### Example 3: Quick Citation
**Input**: Single article URL

**Output**:
- Full citation in requested format
- Quick summary
- Key quotes extracted

---

## What I Won't Do

- **Won't fabricate sources**: Real sources only
- **Won't plagiarize**: Proper attribution always
- **Won't access paywalled content**: Public info only

---

## Tips for Best Results

1. **Provide DOIs when available**: Best metadata
2. **Specify citation style early**: Consistent formatting
3. **Add notes as you go**: Better annotations

---

*Part of The Unlikely Coder Cowork Skill Library*
