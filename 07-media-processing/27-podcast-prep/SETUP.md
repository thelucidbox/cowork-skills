# Podcast Prep — Setup Guide

## Requirements

| Tool | Required | Purpose |
|------|----------|---------|
| ffmpeg | Yes | Core audio processing |
| sox | Optional | Advanced filters |

---

## Installing Dependencies

### macOS (Homebrew)
```bash
brew install ffmpeg sox
```

### Verify Installation
```bash
ffmpeg -version
sox --version
```

---

## Verifying Setup

### Test Command
> "Test podcast prep"

### Expected Result
```
✓ ffmpeg: Installed
✓ sox: Installed (optional features available)
✓ Ready to process audio
```

---

## Configuration

### Processing Defaults
```
input/
└── podcast-config.md
```

```markdown
## Podcast Processing Defaults

### Loudness
- Target: -16 LUFS (podcast standard)
- True peak: -1.5 dB

### Noise Reduction
- Level: Medium
- Preserve voice clarity

### Silence Removal
- Remove: Silences >2 seconds
- Reduce to: 0.5 seconds

### Format
- Output: mp3 320kbps
- Sample rate: 44.1kHz

### Intro/Outro
- Intro: assets/intro.mp3
- Outro: assets/outro.mp3
- Crossfade: 2 seconds
```

---

## Asset Files

For automatic intro/outro:
```
input/
└── assets/
    ├── intro.mp3
    └── outro.mp3
```

---

## Quality Presets

### Podcast Standard
- -16 LUFS
- 44.1kHz
- mp3 or AAC

### YouTube Audio
- -14 LUFS
- 48kHz
- AAC

### High Quality Archive
- No compression
- 48kHz
- WAV or FLAC

---

*Part of The Unlikely Coder Cowork Skill Library*
