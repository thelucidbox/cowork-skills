# Art of Fact — Cowork Skill Library

> **Turn prompts into facts. Real outputs. Real fast.**

**50 AI-powered skills organized into 12 categories.**

> **🔒 Premium:** 50 Financial Dashboards available in `13-premium-workflows/` (not included in public release)

---

## Quick Start

### Load Any Skill Folder → Say "Ready to Work"

```
You: [loads skill folder into Claude]
You: ready to work

Claude: I see you've loaded [Skill Name]. Here's what I can do...
        What would you like me to help with?

You: [describes your need]

Claude: [produces artifact outputs]
```

That's it. Load, trigger, get artifacts.

**See [QUICKSTART.md](./QUICKSTART.md) for the complete guide.**

---

## What Is This?

A collection of **Cowork Skills** — structured capability packages that help Claude perform specific tasks with consistency and quality. Each skill is self-contained with:

- Instructions Claude reads automatically
- Templates and rules for consistent output
- Input/output folders for your files
- Artifact instructions for interactive dashboards and trackers

---

## How Skills Work

### 1. Load the Folder
Open any skill folder in Claude (via Claude Code, Projects, or drag-and-drop).

### 2. Trigger the Skill
Say one of these:
- `ready to work` — Claude asks what you need
- `run [skill name]` — Claude starts immediately
- `help` — Claude explains the skill

### 3. Get Artifacts
Claude produces real outputs:
- Documents (markdown, reports, analyses)
- Interactive dashboards and trackers (Claude artifacts)
- Organized files in the output folder

---

## Folder Structure

```
cowork-skills/
├── README.md           # You are here
├── QUICKSTART.md       # How to use skills
├── CATALOG.md          # Full skill catalog
│
├── 01-productivity-meetings/
│   ├── 01-debrief-engine/
│   ├── 02-prep-kit-generator/
│   ├── 03-weekly-momentum-report/
│   └── 04-decision-capture/
│
├── 02-communication-stakeholders/
│   ├── 05-audience-splitter/
│   ├── 06-feedback-synthesizer/
│   ├── 07-relationship-pulse/
│   └── 08-difficult-conversation-prep/
│
├── 03-content-knowledge/
│   ├── 09-content-atomizer/
│   ├── 10-learning-path-builder/
│   ├── 11-knowledge-capture/
│   └── 12-research-synthesizer/
│
├── 04-projects-planning/
│   ├── 13-kickoff-kit/
│   ├── 14-retro-runner/
│   ├── 15-scope-creep-detector/
│   └── 16-vendor-evaluator/
│
├── 05-operations-admin/
│   ├── 17-expense-processor/
│   ├── 18-contract-scanner/
│   ├── 19-inbox-triage/
│   └── 20-file-archaeologist/
│
├── 06-personal-strategic/
│   ├── 21-goal-tracker/
│   ├── 22-energy-audit/
│   ├── 23-annual-review-prep/
│   ├── 24-network-mapper/
│   └── 25-life-admin-queue/
│
├── 07-media-processing/
│   ├── 26-video-clipper/
│   ├── 27-podcast-prep/
│   ├── 28-screenshot-cleaner/
│   ├── 29-photo-optimizer/
│   ├── 30-video-transcriber/
│   ├── 31-media-format-converter/
│   └── 32-thumbnail-generator/
│
├── 08-digital-recovery/
│   ├── 33-downloads-archaeologist/
│   ├── 34-duplicate-detective/
│   ├── 35-photo-memory-recovery/
│   └── 36-document-time-machine/
│
├── 09-smart-organization/
│   ├── 37-semantic-file-tagger/
│   ├── 38-project-folder-builder/
│   ├── 39-desktop-zero/
│   └── 40-archive-architect/
│
├── 10-research-synthesis/
│   ├── 41-source-collector/
│   ├── 42-competitive-intel/
│   └── 43-literature-mapper/
│
├── 11-communication-automation/
│   ├── 44-newsletter-assembler/
│   ├── 45-social-media-repurposer/
│   └── 46-email-digest-generator/
│
├── 12-life-admin/
│   ├── 47-subscription-auditor/
│   ├── 48-receipt-processor/
│   ├── 49-tax-prep-assembler/
│   └── 50-warranty-tracker/
│
└── 13-premium-workflows/      🔒 PREMIUM (behind paywall)
    ├── 01-tax-deduction-tracker/
    ├── ...
    └── 50-financial-health-scorecard/
```

---

## Each Skill Contains

```
[skill-folder]/
├── SKILL.md           # Main instructions (Claude reads this)
├── SETUP.md           # One-time setup guide
├── context/
│   ├── rules.md       # Output formatting rules
│   └── templates/     # Templates (if applicable)
├── input/             # Drop your source files here
└── output/            # Where artifacts appear
```

---

## Categories at a Glance

| # | Category | Skills | Focus |
|---|----------|--------|-------|
| 01 | Productivity & Meetings | 01-04 | Meetings, decisions, summaries |
| 02 | Communication | 05-08 | Audiences, feedback, relationships |
| 03 | Content & Knowledge | 09-12 | Content, learning, research |
| 04 | Projects & Planning | 13-16 | Kickoffs, retros, vendors |
| 05 | Operations & Admin | 17-20 | Expenses, contracts, files |
| 06 | Personal & Strategic | 21-25 | Goals, energy, reviews |
| 07 | Media Processing | 26-32 | Video, audio, images |
| 08 | Digital Recovery | 33-36 | Downloads, duplicates, photos |
| 09 | Smart Organization | 37-40 | Tagging, folders, archives |
| 10 | Research & Synthesis | 41-43 | Sources, competitors, literature |
| 11 | Communication Automation | 44-46 | Newsletters, social, email |
| 12 | Life Admin | 47-50 | Subscriptions, taxes, warranties |
| **13** | **🔒 Premium Financial** | **01-50** | **Tax, investments, business ops** |

---

## Example Workflows

### Meeting Just Ended
```
Load: 01-debrief-engine
Say: "ready to work"
Drop: your meeting notes
Get: decisions.md, action-tracker.md, follow-up emails
```

### Starting a New Project
```
Load: 13-kickoff-kit
Say: "run kickoff kit for [project description]"
Get: charter, stakeholders, risks, milestone breakdown
```

### Annual Review Coming Up
```
Load: 23-annual-review-prep
Say: "ready to work"
Provide: your year's accomplishments
Get: brag doc, self-review draft, metrics summary
```

### Research Task
```
Load: 12-research-synthesizer
Say: "research [topic]"
Get: executive brief with citations, source comparison
```

---

## Interactive Artifacts

Every skill supports Claude artifacts — interactive dashboards and trackers you can return to:

- **Project Dashboard** — Health score, milestones, risks
- **Goal Tracker** — Progress bars, status indicators
- **Comparison Matrix** — Vendor scoring, decision frameworks
- **Kanban Boards** — Action items, blockers, progress

Just ask: "Create a dashboard artifact" or "Build a tracker I can update"

---

## Requirements

Most skills need only:
- File system access
- Internet access (for research skills)

Some skills need tools:
- **ffmpeg**: Media processing (skills 26-32)
- **OCR**: PDF and image extraction

---

*Part of Art of Fact — Turn prompts into facts.*
