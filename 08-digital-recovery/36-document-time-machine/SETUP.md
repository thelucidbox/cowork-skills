# Document Time Machine — Setup Guide

## Requirements

| Tool | Required |
|------|----------|
| File access | Yes |
| Time Machine access | Recommended |

## Integration Points

### macOS Time Machine
```
Automatic detection of backup drive
```

### Cloud Services
- Google Drive version history
- Dropbox previous versions
- OneDrive version history
- iCloud Drive

---

## Verifying

> "Test document time machine"

```
✓ Local search: Available
✓ Time Machine: Connected
✓ Cloud access: Configured
✓ Ready to search
```

---

## Configuration

```
input/
└── search-config.md
```

```markdown
## Search Settings
- Locations: All
- Include email: Yes
- Date range: Last 2 years
```

---

*Part of Art of Fact Cowork Skill Library*
