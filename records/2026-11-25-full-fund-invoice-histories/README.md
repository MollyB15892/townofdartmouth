# November 25, 2026 — Full-fund invoice histories FY2023–FY2027 received

**Source:** Five Excel workbooks supplied by the requester from Dartmouth Accounting follow-up to Donna Fernandes's November 25 email.  
**Handling:** The original workbooks have been inspected read-only in the private conversation workspace, but **have not been uploaded to the public GitHub repository or Lovable's authenticated private storage**. This directory holds only aggregated metadata, hashes and processing guidance.

Donna supplied the FY2022 full-fund history separately on November 24; this receipt completes the **six fiscal-year files FY2022–FY2027 YTD**, but they overlap earlier vendor/invoice exports and must not be summed with them.

## Source inventory (all received)

| File | Received | Data rows | SHA-256 |
|---|---|---:|---|
| `Invoice_History_By_Fund 2022.xlsx` | Nov 24 | 25,098 | `7f5707cc0a163cd43cc5fd1f5a5949cc1b29e8af0c9f4b42497bb7fcc21bfaac` |
| `Invoice_History_By_Fund_2023.xlsx` | Nov 25 | 24,114 | `934de6295d6f02734468b84649286d1f97c2afd8b29b79eeb1295c3ce541b3f4` |
| `Invoice_History_By_Fund_2024.xlsx` | Nov 25 | 24,628 | `a8553fa8be05467595a2354b16a04b8733b5babd9a2452febe2298edc6e86c5c` |
| `Invoice_History_By_Fund_2025.xlsx` | Nov 25 | 26,246 | `e20b895b08733c8c855047d7382c02e4672996a32eb549595caa6c7abd07e573` |
| `Invoice_History_By_Fund_2026.xlsx` | Nov 25 | 25,171 | `532cb97af3b6417711fa8df3dc8851b33b1795692cddec3c22e94745336ae0cf` |
| `Invoice_History_By_Fund_2027.xlsx` | Nov 25 | 8,707 | `f8a430e76bfa2a2d04b8bb383a7c822b5a222f6aa9776f2a93d0af742a79c3af` |
| **Total entries (not additive to earlier exports)** | | **133,964** | |

- Workbook tab in all six: `INVOICE LIST BY GL ACCOUNT`
- Identical column headers: `VENDOR`, `VENDOR NAME`, `ORG DESC`, `ACCOUNT`, `YEAR`, `PERIOD`, `TYPE`, `AMOUNT`, `WARRANT`, `INVOICE`, `FULL DESC`, `INVOICE DATE`.
- All rows' `YEAR` fields match their filenames (FY2027 incomplete).
- All six contain `INV`, `DIR`, and `CRM` transaction-type codes; exact accounting interpretation still needs confirmation.

## Important classifications

Donna's November 25 email says account prefixes `88` designate **custodial deposits**, and `82` and `90` designate **trust funds**, not departmental budgeted expenses. These amounts should remain in raw records but be **separately classified from departmental-budget expenditure totals**. She previously noted `R`-starting warrants identify **taxpayer refunds**.

| Fiscal year | Warrants starting R (rows) | Raw ACCOUNT cells starting 82 | Starting 88 | Starting 90 |
|---|---:|---:|---:|---:|
| 2022 | 1,368 | 0 | 43 | 0 |
| 2023 | 906 | 0 | 22 | 0 |
| 2024 | 1,146 | 0 | 6 | 0 |
| 2025 | 2,110 | 15 | 184 | 8 |
| 2026 | 1,969 | 9 | 181 | 7 |
| 2027 YTD | 667 | 0 | 0 | 0 |
| **Total** | **8,166** | **24** | **436** | **15** |

**Major caveat:** These are separate filter counts, not mutually exclusive or unique expenses, and should not be summed to calculate excluded dollars without deduplication. **ACCOUNT formatting changes between years:** FY2022–FY2024 and FY2027 often use a formatted `001 -00-000-…` account string, while FY2025–FY2026 use codes like `01000    21201` and `8800015250`. The absence of leading `82`/`90` in older-format sheets **does not prove no trust activity exists**. Confirm the fund/GL code mapping with Donna or official chart of accounts before treating cross-year prefix counts as directly comparable.

The FY2022 full-fund report was previously estimated to overlap six original invoice exports on about 20,173 rows (~80.4%) using preliminary transaction signatures; overlap has **not** been separately calculated or reconciled for FY2023–FY2027. These workbooks are not five new independent pools of expenditures.

## Previously received data remains relevant

- Seven original accounting workbooks received November 12: six vendor/invoice listing exports with **107,601 transaction rows** plus one vendor master with **3,374 rows**.
- Separate DPW gross and pay-type payroll (FY2022–FY2026) received from HR November 19 in a 59-page PDF. Townwide payroll remains a distinct gap; Donna confirmed she did **not** include payroll in original financial reports.
- Combined distinct transaction count and departmental expenditure totals are **not yet verified** across the different overlapping exports.

## Open items before reporting true department spending

1. Preserve original workbooks in approved private storage and verify checksums; do not publish raw identifiers or names.
2. Confirm the chart of accounts and whether codes 82/88/90 mean the same things in both ACCOUNT formats.
3. Classify refundable payments, custody/trust, pass-through payroll deductions, `INV`/`DIR`/`CRM`, capital and grant-funded expenses according to each fiscal year's coding.
4. Match full-fund histories to the earlier invoice exports by transaction identifiers to prevent double counting; identify any unmatched records and their meaning.
5. Obtain townwide payroll by department and relevant fund to create genuine all-in spending comparisons.
6. Reconcile departmental results to audited FY statements/budget basis and keep FY2027 year-to-date separate.

**Status:** Six full-fund histories received; structural validation complete; financial reconciliations not yet complete. No evidence of misuse or unnecessary spending is inferred by these records alone.

**Related:** [Nov 24 Accounting reply](../2026-11-24-accounting-clarification/README.md) and [Nov 25 custody/trust classification](../2026-11-25-accounting-classification/README.md).
