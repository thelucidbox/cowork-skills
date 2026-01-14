# Content Atomizer — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| ffmpeg (for video) | 5 min | Video clip timestamps |
| No Integrations | 0 min | All text atomization |

---

## Primarily Standalone

Content Atomizer works with any text input. No integrations required for core functionality.

---

## Optional: Video Processing

### What You'll Get
- Specific timestamp suggestions for clips
- Automatic scene detection
- Clip extraction commands

### Setup
Ensure ffmpeg is installed:
```bash
# macOS
brew install ffmpeg

# Verify
ffmpeg -version
```

### Usage
When atomizing video content:
> "Atomize this video and suggest clips"

Clips can be extracted with provided ffmpeg commands.

---

## No Setup Required

### How It Works
1. Drop content in input folder (or paste directly)
2. Specify target platforms
3. Receive platform-ready atoms

### Supported Source Formats
- `.md` / `.txt` (articles, posts)
- `.docx` (documents)
- `.pdf` (PDF content)
- Video transcripts
- Presentation exports
- Direct paste

---

## Verifying Setup

### Test Command
> "Test content atomizer"

### Expected Result
```
✓ Ready to atomize content
✓ ffmpeg: [Available/Not installed]
✓ Drop source content in input/ or paste
```

---

## Platform Configuration

### Customize Platform Defaults
```
input/
└── platform-config.md
```

```markdown
## Twitter
- Max thread length: 10 tweets
- Hashtags: #productivity #tech
- Voice: Casual, punchy

## LinkedIn
- Max length: 1200 characters
- Voice: Professional but warm
- Include: Personal angle

## Newsletter
- Style: Conversational
- Length: 200-300 words
- CTA: Link to full content
```

### Adding Custom Platforms
> "Also create a Threads version"
> "Include Instagram caption format"

---

## Voice Matching

### For Better Results
Drop examples of your existing content:
```
input/
└── examples/
    ├── past-twitter-thread.md
    ├── past-linkedin-post.md
    └── newsletter-example.md
```

I'll match your established voice per platform.

---

*Part of Art of Fact Cowork Skill Library*
