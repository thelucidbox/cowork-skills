# File Archaeologist — Setup Guide

## Choose Your Path

| If You Use... | Setup Time | What You Get |
|---------------|------------|--------------|
| Local Folders | 0 min | Full file analysis |
| No Integrations | 0 min | Works immediately |

---

## No Setup Required

File Archaeologist works directly with your file system.

---

## Verifying Setup

### Test Command
> "Test file archaeologist"

### Expected Result
```
✓ File system access: Available
✓ Metadata reading: Available
✓ Ready to organize folders
```

---

## Configuration

### Organization Preferences
```
input/
└── organization-config.md
```

```markdown
## Organization Preferences

### Naming Convention
- Format: YYYY-MM-DD-description.ext
- Lowercase: Yes
- Spaces: Replace with hyphens

### Categories
- documents/
- images/
- installers/
- archives/
- projects/

### Keep Patterns
- *.important.*
- projects/*
- anything with "keep" in name

### Safe to Delete
- *.tmp
- *.DS_Store
- Thumbs.db
- __MACOSX/*
```

---

## Safety Measures

### Built-In Protections
- Never deletes automatically
- Preserves original timestamps
- Creates manifest before changes
- Supports undo via manifest

### Recommended Workflow
1. Run in analysis-only mode first
2. Review manifest and suggestions
3. Apply changes
4. Keep manifest for reference

---

## Protected Locations

Never modifies:
- System folders
- Library folders
- Application bundles
- Hidden system files

---

*Part of Art of Fact Cowork Skill Library*
