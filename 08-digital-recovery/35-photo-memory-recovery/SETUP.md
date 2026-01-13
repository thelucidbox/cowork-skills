# Photo Memory Recovery — Setup Guide

## Requirements

| Tool | Required |
|------|----------|
| exiftool | Recommended |
| File access | Yes |

## Installing exiftool

```bash
# macOS
brew install exiftool

# Windows
# Download from exiftool.org
```

---

## Verifying

> "Test photo memory recovery"

```
✓ exiftool: Installed (optional)
✓ File access: Available
✓ Ready to recover
```

---

## Configuration

```
input/
└── photo-config.md
```

```markdown
## Recovery Settings
- Sources: ~/Pictures, ~/Old Photos
- Output format: YYYY/MM-Month/
- Duplicates: Remove
```

---

## Supported Formats

| Format | Metadata Support |
|--------|-----------------|
| JPEG | Full EXIF |
| PNG | Limited |
| HEIC | Full EXIF |
| RAW | Full EXIF |

---

*Part of The Unlikely Coder Cowork Skill Library*
