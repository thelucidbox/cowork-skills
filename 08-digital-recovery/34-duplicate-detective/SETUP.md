# Duplicate Detective — Setup Guide

## Requirements

| Tool | Required |
|------|----------|
| File system access | Yes |

## Supported Detection Methods

| Method | Accuracy | Speed |
|--------|----------|-------|
| MD5 Hash | Exact match | Fast |
| SHA-256 | Exact match | Medium |
| Fuzzy hash | Near-duplicates | Slow |
| Name matching | Potential duplicates | Fast |

---

## Verifying

> "Test duplicate detective"

```
✓ File access: Available
✓ Hash computation: Working
✓ Ready to scan
```

---

## Configuration

```
input/
└── scan-config.md
```

```markdown
## Scan Settings
- Locations: ~/Documents, ~/Pictures
- Min size: 1MB
- File types: All
- Method: Hash + Name
```

---

*Part of Art of Fact Cowork Skill Library*
