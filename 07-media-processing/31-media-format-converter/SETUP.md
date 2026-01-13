# Media Format Converter — Setup Guide

## Requirements

| Tool | Required | Purpose |
|------|----------|---------|
| ffmpeg | Yes | Video/audio conversion |

---

## Installing ffmpeg

### macOS (Homebrew)
```bash
brew install ffmpeg
```

### Verify
```bash
ffmpeg -version
```

---

## Verifying Setup

### Test Command
> "Test media converter"

### Expected Result
```
✓ ffmpeg: Installed
✓ Video codecs: H.264, H.265, VP9
✓ Audio codecs: AAC, MP3, FLAC
✓ Ready to convert
```

---

## Supported Conversions

### Video
| From | To |
|------|-----|
| MOV | MP4, WebM, AVI |
| MP4 | MOV, WebM, GIF |
| AVI | MP4, MOV |
| MKV | MP4, MOV |

### Audio
| From | To |
|------|-----|
| WAV | MP3, AAC, FLAC |
| FLAC | MP3, AAC, WAV |
| M4A | MP3, WAV |
| MP3 | AAC, WAV |

### Image
| From | To |
|------|-----|
| PNG | WebP, JPG |
| JPG | WebP, PNG |
| HEIC | JPG, PNG |

---

*Part of The Unlikely Coder Cowork Skill Library*
