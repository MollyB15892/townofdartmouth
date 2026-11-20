# November 19, 2026 — Town of Dartmouth DPW public records production

**Document supplied by requester:** `Molly Armando Public Records Request DPW.pdf` (59 pages).  
**Dated:** November 19, 2026.  
**Town correspondent:** Carol Mello, Human Resources Director.  
**Responds to:** Request dated November 10, 2026, for DPW staffing organization and FY2022–FY2026 compensation records.  
**SHA-256 of the original PDF:** `537a57b7b9c4407c3e3d46d98369fa279c5e991525f4bc4468ecb03107c9cc9b`.

> **Original PDF is not yet committed to this repository.** This entry documents the original file and a verified summary of its contents; the PDF remains with the requester. The GitHub connector available to this workflow cannot upload the PDF binary directly. To attach the actual document, use GitHub's **Add file → Upload files** on this folder, preserving the exact original filename and checksum. The public repository would then expose employee names and individual payroll amounts, as contained in the official production; evaluate that publication decision before uploading.

## What the Town formally produced

- **Pages 1–2:** Formal public-records response. The Town confirms receipt of the November 10 request and says that, after a diligent search, it located and enclosed responsive documents. The letter includes Massachusetts public records appeal rights.
- **Page 3:** “Current Organization of the Department of Public Works,” an organization chart naming the Board of Public Works, DPW director and assistant director, and staff organized into Administration & Engineering, Water Pollution Control, Water & Sewer Division, and Services & Infrastructure (Construction/Highway, Solid Waste & Recycling, Fleet Maintenance). The chart also marks several positions **Vacant**.
- **Pages 4–59:** Employee-by-employee FY2022–FY2026 compensation listing. Fields include employee surname, given name, fiscal year, compensation-description code and amount. Entries include `GROSS`, `REGULAR`, `OVERTIME`, `O/T ST`, `PAGER`, `BUYOUT`, `LNGVTY`, `RETRO`, `CLOTH`, `SICK`, `VACA`, `COMP`, `SCADA` and other codes. **GROSS is itself a total row**: do not sum it with the component pay rows or money will be double-counted.

## Important clarification versus the earlier HR email

HR's earlier November 12 response said the Town did not maintain authorized/filled/vacant/FTE reports by DPW division and was checking whether a roster and compensation records were available. The **November 19 production does include an actual organizational chart with names and several labeled vacancies, and a large historical payroll listing**. It does **not** necessarily satisfy the separate request for authorized position counts, annual division-level headcount/FTE calculations, or FY2027 staffing reports; those were previously described as not maintained.

It is therefore **incorrect to continue describing the entire payroll/organization response as "pending."** A detailed production has arrived. Also, **the presence of a current chart with vacancies does not prove that the Town maintains the precise historic division-level FTE reports requested.**

## Data-quality and interpretation guidance

1. **Never add `GROSS` to pay-code entries**. Summarize gross independently; summarize overtime/regular and other earnings codes separately.
2. Different pay codes such as `OVERTIME` and `O/T ST` require definitions before reporting an overtime total. `PAGER` may be a separate standby/on-call category, not a synonym for overtime.
3. Part-year employees, retirement payouts, transfers and changes in roles can make a given person's year-to-year gross pay misleading.
4. The PDF is a generated display, not machine-readable payroll detail by department/division/account. Its compensation lines do not uniformly show a division code on every row.
5. Use page 3 organization structure to formulate staffing hypotheses; verify which historical job/division an employee held *during each fiscal year* before categorizing salaries by division.
6. Respect privacy and avoid inferring employee behavior or productivity from compensation alone. Reports should focus on aggregate staffing and public expenditure patterns unless there is a compelling sourced reason for person-level discussion.

## Recommended analysis and follow-up

- [x] Identify formal reply and date
- [x] Confirm an organizational chart and named staff roster were furnished
- [x] Confirm FY2022–FY2026 gross and pay-code detail were furnished
- [ ] Upload original PDF to a controlled evidence store; consider public-release implications before adding it to this public GitHub repo
- [ ] Count distinct `GROSS` employees by fiscal year (distinct identity keys; check name variations)
- [ ] Compute aggregate gross, overtime, standby and other categories, without double counting
- [ ] Reconcile organization chart roster to FY2026 payroll, noting that employees can appear in payroll but not on today's chart
- [ ] Request or locate existing job/account/division codes to allocate labor costs without assumptions
- [ ] Identify which vacancies were unfilled and for how long, using existing job posting/budget records
- [ ] Reconcile payroll totals to FY2022–FY2026 town budget and enterprise expenses
- [ ] Clarify whether remaining records were withheld, not maintained, or already supplied

**Assessment status:** Intake complete; numerical payroll analysis and verification pending. No allegation of payroll wrongdoing.
