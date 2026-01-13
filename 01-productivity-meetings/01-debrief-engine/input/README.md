# Debrief Engine — Input Folder

## What Goes Here

Drop your meeting notes in this folder before running the debrief engine.

### Accepted Formats

| Format | Notes |
|--------|-------|
| `.txt` | Plain text notes |
| `.md` | Markdown notes |
| `.docx` | Word documents |
| `.pdf` | PDF exports |
| `.m4a` / `.mp3` | Voice memo (will transcribe) |
| Clipboard | Paste directly when prompted |

### File Naming

Name files descriptively for automatic context:
- `2024-01-15-product-sync.md` ✓
- `client-call-acme-corp.txt` ✓
- `notes.txt` ✗ (works but loses context)

### Multiple Meetings

Process one meeting at a time for best results. If you have multiple meetings, either:
1. Run debrief engine separately for each
2. Clearly separate notes with headers: `## Meeting 1: Product Sync`

### Supporting Files

You can also include:
- **Previous debrief outputs**: For continuity
- **Email threads**: Copy-paste relevant context
- **Agenda documents**: Original meeting agenda

---

## Folder Structure

```
input/
├── meeting-notes.md          # Primary notes
├── previous-debrief.md       # Optional: prior context
├── email-thread.txt          # Optional: related emails
└── agenda.pdf                # Optional: meeting agenda
```

---

## Tips

1. **More context = better output**: Include attendee names, dates, prior context
2. **Raw is fine**: Don't clean up notes — the engine handles messy input
3. **Voice memos work**: Drop audio files and transcription happens automatically
4. **Clear when done**: Move processed files to avoid reprocessing
