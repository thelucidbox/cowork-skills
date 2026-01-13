# Social Media Repurposer

**Transform content into platform-optimized social media posts.**

---

## What This Does

Takes long-form content (articles, presentations, videos) and repurposes it into multiple social media posts optimized for different platforms, with appropriate formatting, hashtags, and scheduling suggestions.

| Output | What You Get |
|--------|--------------|
| posts/ | Platform-specific content |
| content-calendar.md | Posting schedule |
| asset-list.md | Required images/media |

---

## Quick Start

### Option 1: Natural Language
> "Turn this blog post into social media content"

### Option 2: Platform Specific
> "Create LinkedIn posts from my presentation"

### Option 3: Campaign Mode
> "Build a week of posts from this article"

---

## What I Need From You

### Required
- **Source content**: What to repurpose

### Optional (Enhances Output)
- **Platforms**: Where to post
- **Tone**: Brand voice
- **Schedule**: Posting frequency

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| Content | Key points, quotes | Manual extraction |
| Platform specs | Character limits, formats | Standard defaults |
| Hashtag research | Relevant tags | Generic tags |

---

## Output Location

```
output/
├── posts/
│   ├── twitter/
│   ├── linkedin/
│   ├── instagram/
│   └── threads/
├── content-calendar.md
└── asset-list.md
```

---

## Examples

### Example 1: Blog to Social
**Input**: 2000-word blog post

**Output**:
- 5 Twitter/X threads
- 3 LinkedIn posts
- 10 individual tweets
- Instagram carousel concept
- Posting schedule

### Example 2: Presentation Repurpose
**Input**: 20-slide presentation

**Output**:
- Key insight posts
- Quote graphics list
- Slide-by-slide breakdown
- Video clip suggestions

### Example 3: Video Content
**Input**: 30-minute video

**Output**:
- Timestamp-based clips
- Quote extractions
- Teaser posts
- Full promotion campaign

---

## What I Won't Do

- **Won't post automatically**: Creates drafts only
- **Won't create images**: Lists what's needed
- **Won't guarantee virality**: Quality content only

---

## Tips for Best Results

1. **Provide key messages**: What matters most
2. **Specify brand voice**: Consistent tone
3. **Include call-to-action**: What should readers do

---

*Part of The Unlikely Coder Cowork Skill Library*
