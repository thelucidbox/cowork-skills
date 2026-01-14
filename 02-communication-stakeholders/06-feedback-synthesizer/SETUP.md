# Feedback Synthesizer — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Google Workspace | 3 min | Gmail feedback threads |
| Apple Ecosystem | 3 min | Mail feedback threads |
| Slack Export | 2 min | Channel discussions |
| No Integrations | 0 min | File-based or paste |

---

## Option 1: Google Workspace

### What You'll Get
- Automatic feedback thread extraction
- Email sentiment context
- Response drafts in your tone

### Setup
```
Settings → Integrations → Gmail → Connect
```

### Usage
> "Synthesize feedback from emails with [customer name]"

---

## Option 2: Apple Ecosystem

### What You'll Get
- Mail.app feedback extraction
- Thread context

### Setup
```
System Settings → Privacy & Security → Mail → Enable
```

---

## Option 3: Slack Export

### What You'll Get
- Channel discussion analysis
- Thread synthesis
- User attribution

### How to Export
1. In Slack: Channel settings → Export
2. Download JSON or text export
3. Drop in input folder

### Alternative
Copy-paste relevant discussions directly.

---

## Option 4: No Integrations

### What You'll Get
Full synthesis functionality via:
- Files in input folder
- Direct paste in conversation
- Manual text input

### Supported Formats
- `.txt` / `.md` (text feedback)
- `.csv` (survey exports)
- `.xlsx` (spreadsheet data)
- `.pdf` (feedback documents)
- Copy-paste (any text)

---

## Verifying Setup

### Test Command
> "Test feedback synthesizer"

### Expected Result
```
✓ Ready to synthesize feedback
✓ Sources: [Files/Email/Standalone]
✓ Drop feedback in input/ or paste directly
```

---

## Input Organization

### For Multiple Sources
```
input/
├── survey-responses.csv
├── email-feedback/
│   ├── thread-1.txt
│   └── thread-2.txt
├── slack-export.json
└── other-feedback.md
```

### For Single Source
```
input/
└── feedback.md
```

### Inline
Just paste feedback in conversation:
> "Synthesize this: [feedback text]"

---

## Survey Format Tips

### CSV Format
```csv
timestamp,respondent,rating,comment
2024-01-15,user@email.com,4,"Great product but docs need work"
```

### If Anonymous
```csv
timestamp,rating,comment
2024-01-15,4,"Great product but docs need work"
```

---

*Part of Art of Fact Cowork Skill Library*
