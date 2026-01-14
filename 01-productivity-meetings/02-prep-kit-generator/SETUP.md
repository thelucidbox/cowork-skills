# Prep Kit Generator — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Google Workspace | 5 min | Calendar events, Gmail history, Contacts |
| Apple Ecosystem | 5 min | Calendar.app, Mail.app, Contacts.app |
| No Integrations | 0 min | Web research + manual context |

---

## Option 1: Google Workspace

### What You'll Get
- Automatic event details and attendee list
- Prior email threads with attendees
- Contact notes and relationship history
- Company info from Google Contacts

### Setup Steps

1. **Enable Google Calendar Access**
   ```
   Settings → Integrations → Google Calendar → Connect
   ```
   Required for automatic event lookup

2. **Enable Gmail Access** (Recommended)
   ```
   Settings → Integrations → Gmail → Connect
   ```
   Surfaces prior conversations

3. **Enable Google Contacts** (Optional)
   ```
   Settings → Integrations → Google Contacts → Connect
   ```
   Adds your notes and relationship context

### Permissions Requested
- Calendar: Read-only (event details, attendees)
- Gmail: Read-only (search related threads)
- Contacts: Read-only (notes and organization)

---

## Option 2: Apple Ecosystem

### What You'll Get
- Calendar.app event details and attendees
- Mail.app conversation history
- Contacts.app relationship notes

### Setup Steps

1. **Grant Calendar Access**
   ```
   System Settings → Privacy & Security → Calendar → Enable for Cowork
   ```

2. **Grant Mail Access** (Recommended)
   ```
   System Settings → Privacy & Security → Mail → Enable for Cowork
   ```

3. **Grant Contacts Access** (Optional)
   ```
   System Settings → Privacy & Security → Contacts → Enable for Cowork
   ```

### Note
First-time access may require Full Disk Access depending on macOS version. Follow system prompts.

---

## Option 3: No Integrations (Standalone Mode)

### What You'll Get
- Web research on attendees (LinkedIn, company sites, news)
- Prep based on information you provide
- All core outputs without automation

### How It Works
Tell me:
- Who's in the meeting (names, companies)
- What it's about
- Any context you have

I'll research publicly available information and generate your prep kit.

### Best For
- External meetings where you have limited history
- Privacy-conscious preparation
- Quick prep without setup

---

## Web Research Setup

Web research works automatically regardless of integration choice.

### What Gets Researched
- LinkedIn profiles (public information)
- Company websites and about pages
- Recent news mentions
- Professional history

### Research Depth Options
- **Quick**: Name + company + role (1-2 min)
- **Standard**: Above + recent news + company context (3-5 min)
- **Deep Dive**: Full research including press, social media, mutual connections (5-10 min)

Specify depth when requesting prep.

---

## Verifying Your Setup

### Test Command
> "Test prep kit integrations"

### Expected Results

**With Integrations:**
```
✓ Calendar: Connected
✓ Email: Connected
✓ Contacts: Connected
✓ Web Research: Available
```

**Standalone:**
```
✓ Web Research: Available
✓ Manual mode active
```

---

## Integration Tips

### For Best Results
- Keep contacts updated with notes
- Use consistent email threads (don't start new chains)
- Add meeting agendas to calendar events

### Privacy Considerations
- Web research uses public information only
- Email search limited to your mailbox
- No data stored beyond session
- Can disable specific integrations anytime

---

*Part of Art of Fact Cowork Skill Library*
