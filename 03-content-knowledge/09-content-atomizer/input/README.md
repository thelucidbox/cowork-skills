# Content Atomizer — Input Folder

## What Goes Here

Your source content to atomize.

### Primary Input: Source Content

| Format | Best For |
|--------|----------|
| `.md` / `.txt` | Blog posts, articles |
| `.docx` | Long-form documents |
| `.pdf` | Published content |
| `.mp4` / `.mov` | Video for clips |
| Transcript | Podcast or video text |

---

## Folder Structure

```
input/
├── source-content.md        # Content to atomize
├── platform-config.md       # Optional: platform preferences
└── examples/                # Optional: your existing content
    ├── twitter-example.md
    └── linkedin-example.md
```

---

## Platform Configuration

```markdown
# platform-config.md

## Twitter
- Max thread: 12 tweets
- Hashtags: #startup #founder
- Voice: Casual, direct

## LinkedIn
- Max length: 1500 chars
- Voice: Professional thought leader
- End with: Question for engagement

## Newsletter
- Style: Conversational
- Feature length: 300 words
- Always include: Link to full piece
```

---

## Voice Examples

For better tone matching, include examples:

```markdown
# examples/twitter-example.md

Here's how I usually write threads:

1/ Big insight that hooks

2/ Why this matters to you

3/ The story behind it
...
```

---

## Tips

1. **More source = more atoms**: 500 words creates fewer than 2000
2. **Highlight the best parts**: "Focus on section 3" helps
3. **Include videos**: For clip timestamp suggestions
4. **Share your voice**: Examples improve matching
