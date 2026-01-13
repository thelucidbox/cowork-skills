# File Archaeologist — Input Folder

## What Goes Here

Configuration files for organization preferences.

### Configuration

| File | Purpose |
|------|---------|
| `organization-config.md` | Naming and categorization preferences |

---

## Configuration Example

```markdown
# organization-config.md

## Naming Convention
- Pattern: YYYY-MM-DD-description
- Case: lowercase
- Separator: hyphens

## Categories
- documents/
- images/
- media/
- archives/
- misc/

## Always Keep
- *.important.*
- projects/*

## Safe to Delete
- *.tmp
- *.DS_Store
- __MACOSX/*
```

---

## Note

The folder to organize is specified in the command, not placed in input/.

> "Organize ~/Downloads"

or

> "Analyze ~/Documents/old-stuff"
