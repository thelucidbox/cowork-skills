# Thumbnail Generator — Setup Guide

## Requirements

| Tool | Required |
|------|----------|
| ffmpeg | Yes |

## Installing

```bash
brew install ffmpeg
```

## Verifying

> "Test thumbnail generator"

```
✓ ffmpeg: Installed
✓ Ready to generate thumbnails
```

---

## Configuration

```
input/
└── thumbnail-config.md
```

```markdown
## Settings
- Size: 1280x720
- Quality: 90
- Avoid: First 5 seconds (black screens)
```

---

*Part of Art of Fact Cowork Skill Library*
