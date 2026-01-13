# Debrief Engine — Output Folder

## What Appears Here

After running the debrief engine, you'll find:

```
output/
├── decisions.md          # All decisions with context
├── action-tracker.md     # Assigned tasks with deadlines
├── open-loops.md         # Unresolved questions
├── follow-ups/
│   ├── team-update.md    # Internal team email draft
│   ├── client-recap.md   # Client-facing email draft
│   └── exec-summary.md   # Executive brief draft
└── future-brief.md       # Context for next meeting
```

---

## File Descriptions

### decisions.md
Every decision captured from the meeting, including:
- What was decided
- Context and rationale
- Any noted dissent
- Revisit triggers

### action-tracker.md
Markdown table of all action items:
- Owner (or flagged as unassigned)
- Task description
- Deadline
- Status
- Notes

### open-loops.md
Questions and issues that weren't resolved:
- Needing resolution (blockers)
- Parking lot (not urgent)

### follow-ups/
Draft emails in three tones:
- **team-update.md**: Casual internal version
- **client-recap.md**: Professional external version
- **exec-summary.md**: Brief leadership version

Review and customize before sending.

### future-brief.md
Context file for your next meeting with these attendees:
- Relationship status
- Open items
- People notes
- Communication preferences

---

## Post-Processing

### Recommended Workflow
1. Review `decisions.md` — confirm accuracy
2. Check `action-tracker.md` — assign TBD owners
3. Choose appropriate follow-up email — edit and send
4. Save `future-brief.md` for next meeting prep

### Archiving
After processing:
- Move outputs to a dated folder: `output/2024-01-15-product-sync/`
- Or integrate into your notes system
- Keep `future-brief.md` accessible for prep-kit-generator

---

## Output Customization

Outputs follow templates in `context/templates/`. Modify those files to change:
- Email formats and tone
- Decision documentation style
- Action tracker columns
- Future brief structure
