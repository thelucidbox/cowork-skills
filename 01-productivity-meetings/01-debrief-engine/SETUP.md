# Debrief Engine — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Google Workspace | 5 min | Auto-pull attendees, prior emails, contact details |
| Apple Ecosystem | 5 min | Calendar integration, Contacts lookup, Mail context |
| No Integrations | 0 min | Full functionality with manual input |

---

## Option 1: Google Workspace

### What You'll Get
- Automatic attendee list from Calendar events
- Prior email thread context from Gmail
- Contact details and roles from Google Contacts

### Setup Steps

1. **Enable Google Calendar Access**
   ```
   Settings → Integrations → Google Calendar → Connect
   ```
   Grant read access to calendar events

2. **Enable Gmail Access** (Optional but recommended)
   ```
   Settings → Integrations → Gmail → Connect
   ```
   Grant read access for context enrichment

3. **Enable Google Contacts** (Optional)
   ```
   Settings → Integrations → Google Contacts → Connect
   ```
   Enables full name and role lookup

### Permissions Requested
- Calendar: Read-only (event details, attendees)
- Gmail: Read-only (search for related threads)
- Contacts: Read-only (name and organization lookup)

---

## Option 2: Apple Ecosystem

### What You'll Get
- Attendee list from Calendar.app events
- Contact details from Contacts.app
- Prior thread context from Mail.app

### Setup Steps

1. **Grant Calendar Access**
   ```
   System Settings → Privacy & Security → Calendar → Enable for Cowork
   ```

2. **Grant Contacts Access**
   ```
   System Settings → Privacy & Security → Contacts → Enable for Cowork
   ```

3. **Grant Mail Access** (Optional)
   ```
   System Settings → Privacy & Security → Mail → Enable for Cowork
   ```

### Note on Apple Mail
Mail integration requires Full Disk Access or specific Mail permissions depending on your macOS version. Follow the prompts when first accessing email context.

---

## Option 3: No Integrations (Standalone Mode)

### What You'll Get
Everything except automatic lookups. You provide:
- Attendee names in your notes or explicitly
- Any prior context you want included
- Email addresses if you want drafts addressed

### How It Works
Simply provide your meeting notes. I'll:
- Extract attendee names from the notes themselves
- Ask clarifying questions if critical info is missing
- Generate all outputs based on what you provide

### This Mode Is Best When
- You're processing notes from external meetings
- You prefer not to connect services
- You're working with confidential/sensitive meetings

---

## Verifying Your Setup

### Test Command
> "Test debrief engine integrations"

### Expected Results

**With Google Workspace:**
```
✓ Calendar: Connected (can read events)
✓ Gmail: Connected (can search threads)
✓ Contacts: Connected (can lookup names)
```

**With Apple Ecosystem:**
```
✓ Calendar: Authorized
✓ Contacts: Authorized
✓ Mail: Authorized (or skipped)
```

**Standalone:**
```
✓ No integrations configured
✓ Manual mode active
```

---

## Integration Troubleshooting

### "Calendar events not found"
- Verify the meeting is on your primary calendar
- Check that the event time matches what you're referencing
- Try providing the exact event title

### "Email context not loading"
- Gmail/Mail access may need re-authorization
- Search is limited to last 90 days by default
- Try providing the email thread directly if urgent

### "Contact lookup failing"
- Name in notes may not match contact exactly
- Try using email address instead of name
- Add missing contacts to your address book

---

## Privacy Notes

- **Calendar**: Only reads events you reference
- **Email**: Searches for threads matching attendee names and meeting topic
- **Contacts**: Lookup only, no modifications
- **All data**: Processed locally, not stored beyond session

---

*Part of Art of Fact Cowork Skill Library*
