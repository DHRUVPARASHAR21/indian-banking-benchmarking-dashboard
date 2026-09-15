# Refresh procedure

## Objective

Update the project for a new reporting year without breaking KPI definitions or historical comparability.

## Steps

1. Create a new branch, for example `refresh/fy2026`.
2. Download or link each bank's annual report and Q4 earnings presentation.
3. Update `docs/sources.md` with the document date, URL, page reference and extraction date.
4. Copy the previous processed dataset to a new year-labelled file before changing values.
5. Standardise all monetary values to ₹ crore and all percentages to decimal values.
6. Confirm reporting basis for each bank. Flag standalone or consolidated differences.
7. Update FY25/FY24 fields in the input table to the new current and prior year values.
8. Recalculate the workbook and inspect the ranking pages, peer median and opportunity narrative.
9. Check for missing values, percentage values entered as whole numbers, negative or zero denominators, and duplicate banks.
10. Export fresh screenshots and update the README's reporting-period reference.
11. Commit the data, documentation and dashboard changes together with a concise change note.

## Minimum QA checks

- Every bank has a primary filing source.
- Every percentage displays in a plausible range.
- Loan growth and deposit growth reconcile to the two year-end balances.
- Cost / income uses operating expense and operating income from the same basis.
- Credit cost uses provision expense and average gross advances from the same basis.
- Dashboard ranks contain no formula errors or duplicate ranks caused by a tie without an explicit tie rule.
