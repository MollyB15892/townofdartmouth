# November 25, 2026 — Donna Fernandes's additional accounting classification rules

**Source:** Follow-up email from Dartmouth Accounting (Donna Fernandes) provided by requester on November 25, 2026.  
**Status:** Email text received and documented. Donna refers to attachments, but **no new attachments from this message were accessible to this repository update**; their filenames, fiscal-year coverage, hashes, row counts, and receipt status are **not verified**. Do not mark remaining yearly reports as received yet.

## New source-grounded distinctions

Donna states that the following account prefixes should **not be treated as departmental payments / departmental budgeted expenditures**:

| Prefix at beginning of Account field | Donna's description | Research treatment |
| --- | --- | --- |
| `88` | Custodial deposits held for designated purposes; not Town expenditures | Separate **custody funds / nondepartmental**, excluded from *departmental operating-spend* aggregates |
| `82` | Trust funds donated for designated purposes, e.g., scholarships; not departmental budgeted expenditures | Separate **trust-fund payments**, excluded from *departmental budgeted-spend* aggregates |
| `90` | Trust funds donated for designated purposes, e.g., scholarships; not departmental budgeted expenditures | Separate **trust-fund payments**, excluded from *departmental budgeted-spend* aggregates |

These exclusions apply **to analysis of departmental budgeted spending**. Keep source transactions intact and make their own category visible for custody/trust accounting, rather than erasing them or treating them as fraud. **Do not infer a transaction is a budget item solely because its prefix differs from 82/88/90**; other rules and transaction codes still apply.

## Previously supplied coding guidance (November 24)

- **Payroll** and employee payroll deductions: NOT included in the original seven accounting workbooks; separate FY2022–2026 **DPW** payroll PDF has been received, not townwide payroll.
- **Taxpayer refunds:** warrants starting with `R`, excluded from department-budget spending.
- **Voluntary payroll deductions/pass-throughs:** present in the supplementary `Invoice_History_By_Fund 2022.xlsx`; Donna specifically noted worksheet rows 1–1731. These can be actual transfers of held money but are not departmental expenditures.
- **Capital expenditures:** included in prior reports. Donna described a capital account segment whose first five digits end in `5`; before implementing this rule, confirm exact field layout and segment boundaries.
- **Gifts, grants, revolving funds:** included in the `Other Funds` export; Donna describes accounts beginning with `4`. This is a **fund-type grouping**, not a blanket exclusion from departmental or program-cost reporting: determine actual classifications using the chart of accounts.
- **Overlaps:** the FY2022 all-fund report overlaps earlier source exports; never sum all sources indiscriminately.
- **FY2027:** year-to-date and incomplete.

## Recommended implementation in the private dashboard

1. Preserve raw `Account` fields as strings (retain prefix information and punctuation); match only normalized **leading** `82`, `88`, `90`. Validate account-code format against the Town's chart of accounts before classifying ambiguous accounts.
2. Use **separate report views**: (a) Department-budget expense analysis; (b) custody/trust/payment flows; (c) raw transaction ledger; (d) reconciliation exceptions.
3. For a working department-cost definition, exclude refund warrants `R*` and pass-through/deduction items alongside the above account prefixes, keeping mutually exclusive classification reasons and the ability to inspect them later.
4. Distinguish actual payments, invoice entries, account transfers, encumbrances, credits and capital; use transaction-type definitions before final amounts.
5. Preserve a dated **classification rule register** with Donna's November 24–25 emails as the provenance and a verification status. No totals recomputed until additional attachments are reviewed and duplicate reports reconciled.

## Open actions

- [x] Record Nov 25 account-prefix rules from Donna's email.
- [ ] Obtain the **actual attached files** she references, if they are additional reports; index filenames, years, hashes, row counts, and compare with earlier workbooks without double counting.
- [ ] Obtain/confirm an official chart of accounts explaining the 82, 88, 90 and capital coding conventions.
- [ ] Reconcile FY2022–2027 annual departmental costs only after payroll, transaction-code interpretation, and overlap checks.
- [ ] Update public research only with nonidentifying, validated summaries; original payment files belong in private storage.

**These entries describe accounting treatment, not findings of inappropriate spending.**
