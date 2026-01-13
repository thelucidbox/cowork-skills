# Screenshot Cleaner — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Image Files | 0 min | Full OCR and organization |
| No Setup | 0 min | Works immediately |

---

## No Setup Required

Screenshot Cleaner uses built-in image analysis and OCR.

---

## Verifying Setup

### Test Command
> "Test screenshot cleaner"

### Expected Result
```
✓ OCR: Available
✓ Image processing: Available
✓ Ready to organize screenshots
```

---

## Configuration

### Organization Preferences
```
input/
└── cleaner-config.md
```

```markdown
## Screenshot Organization

### Categories
- work/
- personal/
- reference/
- errors/

### Naming Format
- Pattern: YYYY-MM-DD-[topic]-[description]
- Case: lowercase
- Separator: hyphens

### Duplicates
- Action: Move to duplicates/
- Similarity threshold: 95%

### Date Handling
- Prefer: EXIF date
- Fallback: File date
```

---

## Supported Formats

- `.png` (most screenshots)
- `.jpg` / `.jpeg`
- `.gif`
- `.heic` (Apple)
- `.webp`

---

## Large Collections

For >500 screenshots:
- May take longer
- Consider batch processing
- Review index for accuracy

---

*Part of The Unlikely Coder Cowork Skill Library*
