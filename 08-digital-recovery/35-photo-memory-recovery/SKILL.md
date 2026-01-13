# Photo Memory Recovery

**Rescue, organize, and restore metadata to scattered photo collections.**

---

## What This Does

Recovers photos from various sources, reconstructs missing metadata (dates, locations, events), identifies people and places, and organizes them into a coherent, browsable collection with timeline and event groupings.

| Output | What You Get |
|--------|--------------|
| recovered/ | Organized photo library |
| timeline/ | Chronological view |
| events/ | Event-based groupings |
| recovery-report.md | Full documentation |

---

## Quick Start

### Option 1: Natural Language
> "Recover and organize my scattered photos"

### Option 2: Metadata Recovery
> "Fix missing dates on my photo collection"

### Option 3: Event Assembly
> "Group photos by events and trips"

---

## What I Need From You

### Required
- **Photo sources**: Folders to scan

### Optional (Enhances Output)
- **Known events**: Dates and names of trips/events
- **People to identify**: Names for face grouping
- **Location hints**: Places you've visited

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| EXIF data | Original metadata | File dates |
| Filename patterns | Date extraction | Sequential naming |
| Content analysis | Location/event guesses | Manual grouping |

---

## Output Location

```
output/
├── recovered/
│   └── YYYY/
│       └── MM-MonthName/
├── timeline/
├── events/
│   └── [Event Name]/
└── recovery-report.md
```

---

## Examples

### Example 1: Legacy Photo Recovery
**Input**: 10,000 photos from old hard drive

**Output**:
- Dates recovered for 8,000 photos
- 50 events identified
- Timeline spanning 15 years
- 200 duplicates removed

### Example 2: Metadata Repair
**Input**: Photos with stripped metadata

**Output**:
- Dates restored from filenames
- Locations inferred from sequences
- Event groupings suggested
- Rename recommendations

### Example 3: Multi-Source Merge
**Input**: Photos from phone, camera, cloud

**Output**:
- Unified timeline
- Duplicates resolved
- Consistent naming
- Complete backup ready

---

## What I Won't Do

- **Won't delete originals**: Works on copies
- **Won't modify without backup**: Safety first
- **Won't guess uncertain data**: Marks as unknown

---

## Tips for Best Results

1. **Provide event dates**: Helps grouping accuracy
2. **Keep originals**: Until recovery verified
3. **Start with one source**: Then merge

---

*Part of The Unlikely Coder Cowork Skill Library*
