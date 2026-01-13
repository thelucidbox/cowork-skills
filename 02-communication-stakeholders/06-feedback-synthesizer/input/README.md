# Feedback Synthesizer — Input Folder

## What Goes Here

All feedback sources you want synthesized.

### Supported Formats

| Format | Best For |
|--------|----------|
| `.csv` | Survey exports |
| `.xlsx` | Spreadsheet data |
| `.txt` | Plain text feedback |
| `.md` | Markdown documents |
| `.pdf` | Feedback reports |
| `.json` | Slack/API exports |

---

## Folder Structure

```
input/
├── surveys/
│   └── customer-survey-q4.csv
├── emails/
│   └── feedback-threads.txt
├── reviews/
│   └── 360-feedback.md
└── other/
    └── slack-export.json
```

Or just put everything at the top level.

---

## CSV Format

### With Attribution
```csv
timestamp,source,rating,comment
2024-01-15,customer@email.com,4,"Great support team"
```

### Anonymous
```csv
timestamp,rating,comment
2024-01-15,4,"Great support team"
```

### Required Columns
- `comment` or `feedback` (the text to analyze)

### Optional Columns
- `timestamp` / `date`
- `source` / `name` / `email`
- `rating` / `score`
- `category` / `type`

---

## Text Formats

### Email Thread Style
```
From: customer@email.com
Date: 2024-01-15

[Feedback text]

---

From: another@email.com
Date: 2024-01-16

[More feedback]
```

### Simple List Style
```
- "Great product, needs better docs" — User A
- "Too expensive" — User B
- "Love the new feature" — User C
```

---

## Tips

1. **Include all feedback**: Don't pre-filter
2. **Preserve attribution**: When you have it
3. **Note context**: What was this feedback about?
4. **Specify anonymity**: If feedback should stay anonymous
