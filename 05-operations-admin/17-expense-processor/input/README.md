# Expense Processor — Input Folder

## What Goes Here

Receipt images to process.

### Structure

```
input/
├── receipt-001.jpg
├── receipt-002.jpg
├── trip-nyc/           # Group by trip
│   ├── dinner-monday.jpg
│   └── uber-tuesday.jpg
└── expense-policy.md   # Optional
```

---

## Supported Formats

- `.jpg` / `.jpeg`
- `.png`
- `.heic`
- `.pdf` (image-based)

---

## Naming Tips

Descriptive names help:
- `2024-01-15-uber.jpg` ✓
- `dinner-client-acme.jpg` ✓
- `IMG_4523.jpg` ✗ (works but less helpful)

---

## Batch Processing

Put all receipts in folder:
> "Process all receipts in input/"

Or by subfolder:
> "Process receipts from trip-nyc/"
