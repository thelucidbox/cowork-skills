# Photo Optimizer — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Image Files | 0 min | Full optimization |
| No Setup | 0 min | Works immediately |

---

## No Setup Required

Photo Optimizer uses built-in image processing capabilities.

---

## Verifying Setup

### Test Command
> "Test photo optimizer"

### Expected Result
```
✓ Image processing: Available
✓ WebP support: Available
✓ Ready to optimize
```

---

## Configuration

### Optimization Presets
```
input/
└── optimizer-config.md
```

```markdown
## Optimization Settings

### Blog Images
- Max width: 1200px
- Quality: 85
- Format: webp

### Thumbnails
- Max width: 300px
- Quality: 80
- Format: webp

### Social Media
- Size: 1080x1080
- Quality: 90
- Format: jpg
```

---

## Supported Formats

### Input
- `.jpg` / `.jpeg`
- `.png`
- `.gif`
- `.webp`
- `.heic`
- `.tiff`

### Output
- `.webp` (recommended)
- `.jpg`
- `.png`

---

*Part of The Unlikely Coder Cowork Skill Library*
