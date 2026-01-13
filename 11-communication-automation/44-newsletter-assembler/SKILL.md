# Newsletter Assembler

**Compile curated newsletters from various content sources automatically.**

---

## What This Does

Gathers content from specified sources, curates based on your criteria, formats into newsletter layouts, and produces ready-to-send email newsletters or digests on any schedule.

| Output | What You Get |
|--------|--------------|
| newsletter.md | Formatted content |
| newsletter.html | Email-ready version |
| content-log.md | Source tracking |

---

## Quick Start

### Option 1: Natural Language
> "Create this week's newsletter from my saved articles"

### Option 2: Curated
> "Build a newsletter on AI developments from the past week"

### Option 3: Team Update
> "Assemble our monthly team newsletter"

---

## What I Need From You

### Required
- **Content sources**: Where to pull from

### Optional (Enhances Output)
- **Sections**: Newsletter structure
- **Tone**: Voice and style
- **Length**: Target word count

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| Saved articles | Curated content | Manual input |
| RSS feeds | Latest posts | — |
| Team updates | News items | Request from team |

---

## Output Location

```
output/
├── newsletter.md
├── newsletter.html
├── content-log.md
└── archives/
    └── [date]-newsletter.md
```

---

## Examples

### Example 1: Industry Newsletter
**Input**: Tech news sources + commentary

**Output**:
- Top stories curated
- Brief summaries
- Your analysis added
- Links organized

### Example 2: Team Newsletter
**Input**: Project updates, wins, announcements

**Output**:
- Section per team/project
- Highlights featured
- Upcoming events
- Recognition section

### Example 3: Personal Digest
**Input**: Bookmarked articles, notes

**Output**:
- Themed sections
- Personal commentary
- Reading recommendations
- Follow-up actions

---

## What I Won't Do

- **Won't plagiarize**: Summaries and links only
- **Won't fabricate news**: Real sources only
- **Won't send without review**: Draft for approval

---

## Tips for Best Results

1. **Save content throughout week**: Better curation
2. **Define clear sections**: Consistent structure
3. **Add your voice**: Makes it personal

---

*Part of The Unlikely Coder Cowork Skill Library*
