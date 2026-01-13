# Expense Processor — Output Folder

## What Appears Here

```
output/
├── expense-report.xlsx        # Main spreadsheet
├── anomalies.md               # Flagged items
├── reimbursement-request.md   # Submit-ready
└── receipts-processed/
    └── [renamed receipts]
```

---

## File Descriptions

### expense-report.xlsx
Complete expense spreadsheet:
- All extracted expenses
- Categorized and dated
- Project codes assigned
- Ready for import to expense system

### anomalies.md
Items needing attention:
- Duplicate candidates
- Unusual amounts
- Unreadable receipts
- Policy flags

### reimbursement-request.md
Submission-ready document:
- Summary totals
- Expense breakdown
- Certification section

### receipts-processed/
Organized receipts:
- Renamed with date-vendor format
- Matched to spreadsheet entries
- Originals preserved

---

## Using the Outputs

### For Reimbursement
1. Review `anomalies.md` first
2. Resolve any flagged items
3. Submit `expense-report.xlsx`
4. Attach `receipts-processed/` folder

### For Accounting
Import spreadsheet to expense system.
