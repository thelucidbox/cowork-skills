# Content Atomizer

**Break long-form content into platform-specific pieces—each atom stands alone.**

---

## What This Does

Takes your long-form content—blog post, video transcript, presentation—and atomizes it into platform-specific pieces. Each output is tailored to its platform's format and audience expectations. Turn one piece of content into a week's worth of social media, newsletter segments, and quote cards.

| Output | What You Get |
|--------|--------------|
| twitter-thread.md | Numbered thread with hooks |
| linkedin-post.md | Professional narrative format |
| newsletter-section.md | Email-ready segment |
| quote-cards.md | Visual quote extractions |
| video-clips.md | Suggested clip timestamps |

---

## Quick Start

### Option 1: Natural Language
> "Atomize my blog post into social content"

### Option 2: With File
> "Run content atomizer on article.md in input/"

### Option 3: Platform-Specific
> "Turn this into a Twitter thread and LinkedIn post"

---

## What I Need From You

### Required
- **Source content**: The long-form piece to atomize
- **Target platforms**: Where you want to publish (or use defaults)

### Optional (Enhances Output)
- **Key message**: What's the one thing you want people to remember?
- **Audience context**: Who follows you on each platform?
- **Voice notes**: Any platform-specific tone preferences
- **Hashtags**: Your standard hashtags per platform
- **CTA**: What action you want (follow, subscribe, read more)

---

## What I'll Pull Automatically

| Integration | What I Get | Fallback |
|-------------|-----------|----------|
| Local Files | Source content from input folder | Paste directly |
| Video (ffmpeg) | Suggested clip timestamps | Manual timestamp notes |

---

## Output Location

```
output/
└── atoms/
    ├── twitter-thread.md     # Thread with hooks
    ├── linkedin-post.md      # Professional format
    ├── newsletter-section.md # Email segment
    ├── quote-cards.md        # Visual quotes
    └── video-clips.md        # Clip suggestions
```

---

## Examples

### Example 1: Blog Post Atomization
**Input**: 2000-word blog post on productivity

**Output**:
- Twitter thread: 8 tweets, hook first, CTA last
- LinkedIn post: 1200 characters, professional angle
- Newsletter section: Key insights + link to full post
- Quote cards: 4 standalone quotes for Instagram/graphics
- Clip suggestions: If video exists, key moments

### Example 2: Podcast Episode
**Input**: 45-minute podcast transcript

**Output**:
- Twitter thread: Best insights as thread
- LinkedIn post: Key takeaway narrative
- Quote cards: Guest quotes highlighted
- Video clips: 5 suggested 30-60 second clips with timestamps

### Example 3: Presentation
**Input**: Conference talk slides and transcript

**Output**:
- Twitter thread: Main points as thread
- LinkedIn post: Professional recap
- Newsletter section: Summary for subscribers
- Quote cards: Key slide quotes
- Video clips: Strongest segments

---

## What I Won't Do

- **Won't post for you**: Creates ready-to-post content, you publish
- **Won't pad thin content**: If source is thin, atoms will be thin
- **Won't misrepresent**: Each atom reflects original accurately
- **Won't violate platform norms**: Follows each platform's conventions
- **Won't add fabricated quotes**: Only extracts what's actually in source

---

## Tips for Best Results

1. **Provide rich source**: More depth = more atoms possible
2. **Highlight key sections**: "The part about X is strongest" focuses extraction
3. **Share platform context**: "My LinkedIn is B2B, Twitter is casual"
4. **Include existing threads**: Show me your past posts for voice matching
5. **Specify call-to-action**: What do you want people to do?

---

## Troubleshooting

### "Atoms feel repetitive"
Source may have one main point. That's okay—fewer, stronger atoms beat forced variety.

### "Thread is too long/short"
Specify: "Max 5 tweets" or "Need at least 10 tweets for algorithm."

### "Tone doesn't match my brand"
Share examples of your existing content on each platform. I'll match your voice.

### "Missing platform I need"
Ask: "Also create a [platform] version" and I'll add it.

---

*Part of The Unlikely Coder Cowork Skill Library*
