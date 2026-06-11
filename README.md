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
| `BUG-0006` | PMDB-001 | Dashboard status filter (Ongoing / Completed / Draft) has no effect on project list | OPEN |
| `BUG-0007` | FEED-002 | Feed status tabs (All / Ongoing / Completed) do not filter the project feed | OPEN |
| `BUG-0008` | PJDG-003 | Pinned document status is not retained after page refresh | OPEN |

## Test Plan Reference

Bug reports in this repository are based on the KiwiSoda test plan executed from May-June by tester RADR-R.

---

```
/* Please don't share this information to others recklessly,
** However, you may use this as the basis for your software testing endeavors. */
```