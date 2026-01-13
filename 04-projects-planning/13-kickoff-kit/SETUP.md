# Kickoff Kit — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Org Templates | 5 min | Matches your formats |
| No Integrations | 0 min | Best-practice templates |

---

## Primarily Standalone

Kickoff Kit creates complete project documentation without external dependencies.

---

## Optional: Use Your Templates

### What You'll Get
- Outputs match your organization's formats
- Consistent with existing projects
- Familiar structure for stakeholders

### Setup
```
input/
└── templates/
    ├── charter-template.md
    ├── stakeholder-template.md
    └── risk-template.md
```

I'll match your format while filling in content.

---

## No Setup Required

### Default Templates Include
- Project charter with scope/out-of-scope
- RACI-style stakeholder mapping
- Risk register with probability/impact
- Milestone breakdown with owners

---

## Verifying Setup

### Test Command
> "Test kickoff kit"

### Expected Result
```
✓ Ready to generate kickoff packages
✓ Templates: [Custom/Default]
✓ Describe your project to begin
```

---

## Configuration Options

### For Recurring Project Types
```
input/
└── kickoff-config.md
```

```markdown
## Project Defaults

### Milestone Duration
- Standard: 2 weeks
- Sprint length: [if using agile]

### Risk Categories
- Technical
- Resource
- External
- Organizational

### Stakeholder Groups
- Always include: [standard stakeholders]
- Always consult: [review groups]

### Templates
- Charter: Use standard template
- Risks: Use RAID format
```

---

## Template Customization

### Minimal Charter
> "Create a minimal kickoff kit—just essential elements"

### Comprehensive
> "Full kickoff kit with detailed risk analysis"

### Agile Format
> "Create kickoff kit in agile format with epics and stories"

---

*Part of The Unlikely Coder Cowork Skill Library*
