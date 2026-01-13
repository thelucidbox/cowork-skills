# Podcast Prep — Input Folder

## What Goes Here

Raw audio files and assets.

### Audio Files

Place recordings here:
- `.mp3`
- `.wav`
- `.m4a`
- `.aiff`
- `.flac`

### Assets (Optional)

```
input/
├── raw-episode.mp3       # Your recording
└── assets/
    ├── intro.mp3         # Episode intro
    └── outro.mp3         # Episode outro
```

---

## Configuration

```markdown
# podcast-config.md

## This Episode

### Loudness
- Target: -16 LUFS

### Processing
- Noise reduction: Medium
- Remove long silences: Yes

### Assembly
- Add intro: Yes
- Add outro: Yes
```

---

## Multi-Track Input

For separate tracks:
```
input/
├── host-track.wav
└── guest-track.wav
```

Specify: "Combine host and guest tracks"
