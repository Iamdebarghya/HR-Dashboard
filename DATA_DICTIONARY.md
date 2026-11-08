# HR Workbook: Data Dictionary Template

Confirm these fields against the source workbook before using them. Names below describe common HR measures and are not a claim that every field exists in the current file.

| Field | Meaning | Validation |
|---|---|---|
| Employee ID | Unique employee key | Must be unique and non-null |
| Department | Employee's organizational unit | Standardize labels |
| Gender | Recorded gender category | Preserve source categories |
| Salary | Compensation amount | Numeric, non-negative, currency documented |
| Performance Rating | Recorded performance category | Confirm scale and missing-value meaning |

## Recommended checks
- Count duplicate and blank employee identifiers.
- Check missing department and salary values.
- Confirm salary units and pay frequency.
- Confirm the performance-rating scale with the data owner.
- Never infer sensitive attributes or use the dashboard as the sole basis for employment decisions.
