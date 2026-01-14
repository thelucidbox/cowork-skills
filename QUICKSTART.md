# Art of Fact Skills — Quick Start Guide

> **Turn prompts into facts. Real outputs. Real fast.**

## How to Use Any Skill

### Step 1: Load the Folder
Open the skill folder in Claude (via Claude Code, Claude.ai Projects, or drag-and-drop).

```
/Users/you/cowork-skills/01-productivity-meetings/01-debrief-engine/
```

### Step 2: Say the Magic Words
Type one of these to get started:

| Trigger | What Happens |
|---------|--------------|
| `ready to work` | Claude reads your context and asks what you need |
| `run [skill name]` | Claude immediately starts the workflow |
| `help` | Claude explains what this skill does |

### Step 3: Get Your Artifact
Claude produces real outputs — documents, dashboards, trackers, analyses — not just chat.

---

## Example Session

```
You: ready to work

Claude: I see you've loaded the Debrief Engine skill. I can transform your
meeting notes into structured outputs:
- Decisions documented
- Action items assigned
- Follow-up emails drafted

Drop your meeting notes or describe what happened, and I'll get started.

You: [pastes messy meeting notes]

Claude: [produces decisions.md, action-tracker.md, follow-ups/]
```

---

## Skill Folder Structure

Every skill folder contains:

```
skill-name/
├── SKILL.md          # Instructions Claude reads automatically
├── SETUP.md          # One-time setup (if needed)
├── context/
│   └── rules.md      # Skill-specific rules
├── input/            # Drop your source files here
└── output/           # Where artifacts appear
```

---

## Tips for Best Results

1. **Load the whole folder** — Claude needs SKILL.md to understand what to do
2. **Use input/** — Drop source files there for consistent processing
3. **Be direct** — "Run debrief on these notes" beats lengthy explanations
4. **Request artifacts** — Ask for dashboards, trackers, visualizations
5. **Iterate** — Say "update the tracker" or "revise the output"

---

## Available Skills by Category

### Productivity & Meetings
- Debrief Engine — Meeting notes → decisions + actions
- Prep Kit Generator — Calendar event → full meeting prep
- Weekly Momentum Report — Notes → wins, blockers, priorities
- Decision Capture — Situation → decision framework

### Communication
- Feedback Synthesizer — Scattered feedback → patterns + priorities
- Relationship Pulse — Track and maintain your network
- Audience Splitter — One message → versions for different audiences

### Content & Knowledge
- Content Atomizer — Long-form → platform-specific pieces
- Learning Path Builder — Skill goal → complete curriculum
- Research Synthesizer — Multiple sources → cited brief

### Projects & Planning
- Kickoff Kit — Project description → charter, stakeholders, risks
- Retro Runner — Project notes → patterns + experiments
- Scope Creep Detector — Original vs current → drift analysis
- Vendor Evaluator — Options → comparison matrix + recommendation

### Personal & Strategic
- Goal Tracker — Goals + notes → status dashboard
- Energy Audit — Calendar + notes → patterns + optimizations
- Annual Review Prep — Year of work → brag doc + self-review

### Research & Synthesis
- Competitive Intel — Competitors → landscape analysis
- Literature Mapper — Sources → connection map
- Source Collector — URLs + docs → organized bibliography

### Operations
- Contract Scanner — Contract → key terms + red flags
- Expense Processor — Receipts → organized expense report
- Inbox Triage — Email pile → prioritized action list

### Media Processing
- Video Transcriber — Video → searchable transcript
- Screenshot Cleaner — Screenshot pile → organized archive
- Podcast Prep — Topic → research + outline

### Organization
- Project Folder Builder — Project type → complete structure
- Desktop Zero — Messy desktop → organized files
- Semantic File Tagger — Files → intelligent categorization

---

## Creating Artifacts

Every skill can produce interactive Claude artifacts. Just ask:

> "Create a dashboard artifact for this"
> "Build a tracker I can return to"
> "Make an interactive checklist"

See each skill's SKILL.md for specific artifact options.

---

*Part of Art of Fact — Turn prompts into facts.*
