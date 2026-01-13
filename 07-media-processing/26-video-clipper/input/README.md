# Video Clipper — Input Folder

## What Goes Here

Video files to process.

### Supported Formats

- `.mp4` (recommended)
- `.mov`
- `.avi`
- `.mkv`
- `.webm`

---

## Structure

```
input/
├── video-to-clip.mp4     # Your source video
├── transcript.md         # Optional: existing transcript
└── clipper-config.md     # Optional: settings
```

---

## Providing Transcripts

If you have a transcript:
```markdown
# transcript.md

00:00 - Introduction
00:45 - "Here's the key insight about AI..."
02:30 - Q&A begins
05:15 - "The most important thing to remember..."
```

Timestamps help find moments faster.

---

## Large Files

For very large files:
- Provide timestamp hints when possible
- Allow extra processing time
- Consider lower resolution for drafts
