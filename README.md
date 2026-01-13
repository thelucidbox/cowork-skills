# The Unlikely Coder — Cowork Skill Library

**50 AI-powered skills organized into 12 categories.**

---

## What Is This?

A collection of "Cowork Skills" — structured capability packages that help AI assistants perform specific tasks with consistency and quality. Each skill is self-contained with documentation, templates, and guidelines.

---

## Folder Structure

```
cowork-skills/
├── README.md
├── CATALOG.md
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
└── 12-life-admin/
    ├── 47-subscription-auditor/
    ├── 48-receipt-processor/
    ├── 49-tax-prep-assembler/
    └── 50-warranty-tracker/
```

---

## How to Use

### 1. Browse by Category
Navigate to the category folder that matches your need.

### 2. Choose a Skill
Open the skill folder and read `SKILL.md` for full documentation.

### 3. Check Setup (if needed)
Review `SETUP.md` for any required integrations or tools.

### 4. Invoke the Skill
Use natural language or the example prompts provided.

---

## Each Skill Contains

```
[skill-folder]/
├── SKILL.md           # Main documentation
├── SETUP.md           # Setup & integration guide
├── context/
│   ├── rules.md       # Output formatting rules
│   └── templates/     # Templates (if applicable)
├── input/
│   └── README.md      # What goes in input
└── output/
    └── README.md      # What appears in output
```

---

## Categories at a Glance

| # | Category | Skills | Focus |
|---|----------|--------|-------|
| 01 | Productivity & Meetings | 01-04 | Meetings, decisions, summaries |
| 02 | Communication & Stakeholders | 05-08 | Audiences, feedback, relationships |
| 03 | Content & Knowledge | 09-12 | Content, learning, research |
| 04 | Projects & Planning | 13-16 | Kickoffs, retros, vendors |
| 05 | Operations & Admin | 17-20 | Expenses, contracts, files |
| 06 | Personal & Strategic | 21-25 | Goals, energy, reviews |
| 07 | Media & Processing | 26-32 | Video, audio, images |
| 08 | Digital Recovery | 33-36 | Downloads, duplicates, photos |
| 09 | Smart Organization | 37-40 | Tagging, folders, archives |
| 10 | Research & Synthesis | 41-43 | Sources, competitors, literature |
| 11 | Communication Automation | 44-46 | Newsletters, social, email |
| 12 | Life Admin | 47-50 | Subscriptions, taxes, warranties |

---

## Quick Start Examples

### Clean up my digital life
```
"Clean up my Downloads folder"
→ 08-digital-recovery/33-downloads-archaeologist

"Find duplicate files"
→ 08-digital-recovery/34-duplicate-detective

"Organize my desktop"
→ 09-smart-organization/39-desktop-zero
```

### Prepare for something
```
"Prepare for my meeting with stakeholders"
→ 01-productivity-meetings/02-prep-kit-generator

"Help me prepare for my annual review"
→ 06-personal-strategic/23-annual-review-prep

"Prepare for tax season"
→ 12-life-admin/49-tax-prep-assembler
```

### Process media
```
"Transcribe this video"
→ 07-media-processing/30-video-transcriber

"Create thumbnails for my videos"
→ 07-media-processing/32-thumbnail-generator

"Convert this video to MP4"
→ 07-media-processing/31-media-format-converter
```

---

## Requirements

Most skills require only:
- File system access
- Internet access (for research skills)

Specific tools for some skills:
- **ffmpeg**: Media skills (27, 30, 31, 32)
- **OCR**: PDF and image extraction

---

*Created by The Unlikely Coder*
*Part of the Cowork Skill Library*
