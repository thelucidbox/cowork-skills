# Video Transcriber — Setup Guide

## Requirements

| Tool | Required | Purpose |
|------|----------|---------|
| ffmpeg | Yes | Audio extraction |

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
> "Test video transcriber"

### Expected Result
```
✓ ffmpeg: Installed
✓ Transcription: Available
✓ Ready to transcribe videos
```

---

## Supported Formats

### Video Input
- `.mp4`
- `.mov`
- `.avi`
- `.mkv`
- `.webm`

### Transcript Output
- `.md` (Markdown)
- `.txt` (Plain text)
- `.srt` (Subtitles)
- `.vtt` (Web subtitles)

---

## Configuration

```
input/
└── transcribe-config.md
```

```markdown
## Transcription Settings

### Output Formats
- Transcript: md
- Subtitles: srt

### Timestamps
- In transcript: Every 30 seconds
- In subtitles: Standard

### Speakers
- Detect: Yes
- Names: [List if known]
```

---

*Part of The Unlikely Coder Cowork Skill Library*
