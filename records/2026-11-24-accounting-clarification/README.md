# November 24, 2026 — Accounting clarification and additional FY2022 fund history

**Correspondent:** Donna Fernandes, Town of Dartmouth Accounting.  
**Requester:** Molly Armando.  
**Status:** Town follow-up email received and new FY2022 workbook inventoried; reconciliation pending.

## Accounting Department's clarification (paraphrased from email supplied by requester)

Donna states, **to the best of her knowledge**, that the previously provided expenditure reports cover town expenditures except:
- taxpayer refunds, which she explains are not charged to departmental budgets;
- possibly some employee reimbursements;
- **payroll and employee payroll deductions were NOT included in the original seven reports**.

The prior `Other Funds Expenditures 2022-2026.xlsx` file covers school cafeteria spending, gifts, grants and revolving accounts (examples: recreation, park, conservation). **Capital expenditures are included** in the original accounting reports. Per Donna's explanation, the first five digits of capital account coding end in **5**, while gift/grant/revolving fund account coding begins with **4**. This is vendor-supplied mapping guidance from Accounting and should be checked against the actual account segment definitions before automatic classification.

Donna also supplied a new report, `Invoice_History_By_Fund 2022.xlsx`, and offered to run the **remaining fiscal years** in the same format if helpful. She cautioned that the new report includes payments that are *not* department expenses (employee voluntary deductions or other pass-throughs). She identified worksheet **rows 1–1731** as containing such transactions; taxpayer refunds are identifiable through warrants beginning with **R**.

### What this means for the research

**No immediate need to request separate vendor-expenditure extracts from each town department.** The existing original reports, per Accounting, are broad across departments, enterprise funds and special funds. The main missing direct-cost category is **municipal payroll** outside the separately received DPW payroll production; benefits and other categories still need reconciliation to the detailed accounting codes and authoritative fiscal statements. Individual contracts, work volumes, personnel FTEs and outputs may require targeted requests to departments.

The separate FY2022 history is **not a new independent pool of FY2022 spending to sum on top of the existing six exports**.

## Additional FY2022 workbook inspection (read-only)

| Field | Finding |
| --- | --- |
| Source filename | `Invoice_History_By_Fund 2022.xlsx` |
| SHA-256 | `7f5707cc0a163cd43cc5fd1f5a5949cc1b29e8af0c9f4b42497bb7fcc21bfaac` |
| Workbook sheet | `INVOICE LIST BY GL ACCOUNT` |
| Excel rows incl. header | 25,099 |
| Data rows excluding header | **25,098** |
| Columns | Vendor ID; Vendor Name; Org Desc; Account; Year; Period; Type; Amount; Warrant; Invoice; Full Desc; Invoice Date |
| Rows 2–1731 | **1,730** data rows flagged by Donna as containing deductions/pass-through items; exclude from departmental-spending reports pending classification |
| Refund warrants | **1,368** data rows where Warrant begins with `R` (provisionally exclude from departmental spending); not in the first 1,730 data rows |
| Overlap test | Approx. **20,173 of 25,098** FY2022 rows matched entries from the six earlier invoice listings by vendor/year/type/amount/warrant/invoice/date; **~80.4%** of the new file appears to overlap. This is only a preliminary signature match; it is not ledger-level reconciliation. |
| Remaining unmatched rows after above exclusions | **~1,845**, across categories including Veterans Service–Other, agency deposits, encumbrances, fire district remittances, and project funds; these are **not automatically additional departmental expenses**. |

**Privacy:** The original 2022 workbook contains names and payment/refund transactions (including possible taxpayer identities). Keep it in private encrypted storage. Only metadata, aggregate observations and source checksum are published here. The original Excel workbook has **not** been uploaded to this public GitHub repository or to the private Lovable app by this action.

## November 25, 2026 — additional account-prefix clarification

Donna subsequently clarified that **`88` accounts are custody deposits (not Town expenditures)** and **`82` and `90` accounts are trust funds for designated purposes (not departmental budgeted spending)**. These should be separately accounted for and **excluded from department-budget expenditure calculations** without deleting them from the raw ledger.

She referred to additional attachments, but **no new files from the November 25 email were available for verification during this update**. Therefore do not label the remaining-year reports received or claim to know their row counts. See [classification rules, exclusions and verification status](../2026-11-25-accounting-classification/README.md).

## Updated gaps

1. **Need the rest of the same FY-by-fund report:** Donna offered remaining FY2023–FY2026 and FY2027 YTD; request them if a fully consistent fund/account-based history is needed (very likely useful for a department-by-department hub). Clarify whether each report includes the same payroll-deduction/pass-through/refund sections, so they can be isolated.
2. **Need all-department payroll:** The seven initial Excel books do not include payroll. The separate 59-page DPW payroll response is already received; check whether a town-/school-wide payroll extract was previously requested, then submit a targeted request to the appropriate custodian if not.
3. **Need accounting definitions:** Obtain account-code mapping / chart of accounts and transaction-type definitions, how to identify transfers/refunds/pass-throughs and cleared versus invoice dates, and how to avoid double counting across funds.
4. **Need reconcile before publishing totals:** Compare each fund's appropriate annual net spending to town budgets, audited statements and state Schedule A on the same accounting basis. Do not sum payroll deduction liabilities, tax refunds, or interfund transfers as departmental operating expenditures.
5. **Department completeness:** Existing records include departmental expenditure data, but the *all-in cost of a service or department* still needs payroll, allocated benefits, and accurate general-/enterprise-/grant-funded classifications.

## Status

- [x] Original seven financial workbooks received November 12
- [x] Follow-up financial completeness email sent November 24
- [x] Donna's response received and categorized November 24
- [x] Additional FY2022 fund-level report received and mechanically inspected November 24
- [ ] Remaining FY2023–FY2026 / FY2027 YTD same-format exports requested (**not yet sent**)
- [ ] Additional payroll request confirmed or sent (**not yet confirmed**)
- [ ] Full accounting definition / reconciliation work completed

**No finding of waste, fraud, or misconduct.** Financial comparability and classification remain open.
