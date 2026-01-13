# Video Clipper — Setup Guide

## Requirements

| Requirement | Status | Notes |
|-------------|--------|-------|
| ffmpeg | Required | Video processing |
| Transcription | Optional | For speech search |

---

## Installing ffmpeg

### macOS (Homebrew)
```bash
brew install ffmpeg
```

### Verify Installation
```bash
ffmpeg -version
```

---

## Verifying Setup

### Test Command
> "Test video clipper"

### Expected Result
```
✓ ffmpeg: Installed (version X.X)
✓ Ready to process videos
```

---

## Supported Formats

### Input
- `.mp4` (recommended)
- `.mov`
- `.avi`
- `.mkv`
- `.webm`

### Output
- `.mp4` (default)
- `.mov`
- `.gif` (short clips)

---

## Configuration

### Default Settings
```
input/
└── clipper-config.md
```

```markdown
## Clip Settings

### Default Duration
- Min: 15 seconds
- Max: 90 seconds

### Quality
- Match source (default)
- Or: 1080p / 720p

### Format
- Output: mp4

### Thumbnails
- Generate: Yes
- At: 3 seconds into clip
```

---

## Large File Handling

For videos >1GB:
- Processing takes longer
- Consider providing timestamp hints
- Transcription helps targeting

---

*Part of The Unlikely Coder Cowork Skill Library*
