# Thumbnail Generator

**Generate thumbnails from video files automatically.**

---

## What This Does

Takes video files and generates thumbnail images. Intelligently selects frames avoiding black screens, prefers faces or action, includes timestamps, and can create thumbnail grids for video preview.

| Output | What You Get |
|--------|--------------|
| thumbnails/ | Individual thumbnail images |
| grids/ | Thumbnail grid previews |
| thumbnail-manifest.md | Index of all thumbnails |

---

## Quick Start

### Option 1: Natural Language
> "Generate thumbnails for this video"

### Option 2: Multiple Videos
> "Create thumbnails for all videos in folder"

### Option 3: Grid Mode
> "Create a thumbnail grid showing the whole video"

---

## What I Need From You

### Required
- **Video files**: Source videos

### Optional (Enhances Output)
- **Timestamp**: Specific moment to capture
- **Count**: How many thumbnails per video
- **Size**: Output dimensions

---

## What I'll Pull Automatically

| Integration | What I Get | Fallback |
|-------------|-----------|----------|
| ffmpeg | Frame extraction | Required |

---

## Output Location

```
output/
├── thumbnails/
│   └── video-name-thumb.jpg
├── grids/
│   └── video-name-grid.jpg
└── thumbnail-manifest.md
```

---

## Examples

### Example 1: Single Thumbnail
**Input**: 10-minute video

**Output**:
- Best frame selected (avoiding black)
- 1280x720 thumbnail
- Timestamp noted

### Example 2: Thumbnail Grid
**Input**: 1-hour video

**Output**:
- 4x4 grid of frames
- Evenly spaced through video
- Preview of entire content

### Example 3: Batch Processing
**Input**: 20 video files

**Output**:
- Thumbnail per video
- Consistent sizing
- Manifest for reference

---

## What I Won't Do

- **Won't select blurry frames**: Quality filtering
- **Won't choose black screens**: Smart avoidance
- **Won't modify video**: Thumbnails only

---

## Tips for Best Results

1. **Specify timestamp**: If you know the best moment
2. **Request multiple**: Choose from options
3. **Grid for preview**: Shows content spread

---

*Part of The Unlikely Coder Cowork Skill Library*
