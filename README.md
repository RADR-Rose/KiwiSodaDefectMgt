# KiwiSodaDefectMgt

Defect management repository for the KiwiSoda project.

## How to use

- Each defect is stored as a folder under `BUG-*`.
- Inside each folder, keep:
  - `*.txt` bug report (structured template)
  - optional `*.log` files
  - optional screenshots/images

## Bug ID Convention

Bug IDs follow the format `BUG-XXXX_<TEST_CASE_ID>_<Short_Title>`.
For defects discovered outside the test plan (e.g., exploratory testing),
a placeholder test case ID of `UI-XXX` or similar is used in place of a TCM ID.

## Current bugs

| Bug ID | Test Case | Title | Status |
|--------|-----------|-------|--------|
| `BUG-0001` | FPAS-001 | Forgot Password reset link redirects to login page | OPEN |
| `BUG-0002` | CMOD-001 | Hidden comment remains visible in post after moderation action | OPEN |
| `BUG-0003` | PLAT-001 | Saving Office Information in Platform Settings logs out the admin session | OPEN |
| `BUG-0004` | PMPG-003 | Projects Time Filter does not filter results; all projects remain displayed | OPEN |
| `BUG-0005` | UI-001 (Exploratory) | Search bar in PM Dashboard overlaps the profile settings button in top nav | OPEN |

## Test Plan Reference

Bug reports in this repository are based on the KiwiSoda test plan executed on 06/08–06/09/2026 by tester RADR-R.

---

```
/* Please don't share this information to others recklessly,
** However, you may use this as the basis for your software testing endeavors. */
```