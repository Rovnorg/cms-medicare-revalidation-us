# Medicare revalidation due dates by state (CMS, November 2026)

An open, aggregate dataset of Medicare revalidation due dates by state, built from public CMS data. It contains no provider names, no NPIs and no patient data.

- Compiled by Rōvn (https://rovn.to). Rōvn is not affiliated with Rivon Health.
- Methodology and charts: https://rovn.to/research/medicare-revalidation
- Free lookup by NPI or name: https://rovn.to/medicare-revalidation-lookup

## Source
- **Data:** the Centers for Medicare & Medicaid Services (CMS) Revalidation Due Date List, from the CMS public data API.
- **Edition:** `2026-11-01`
- **Dataset ID:** `3746498e-874d-45d8-9c69-68603cafea60`

## What is in this file
`medicare-revalidation-state-totals-2026-11.csv` has one row per state for 15 states:
AZ, CA, FL, GA, IL, MA, MI, NC, NJ, NY, OH, PA, TN, TX and VA.

| Column | Meaning |
|---|---|
| `total_medicare_enrollments` | enrollments listed for the state |
| `posted_revalidation_due_dates` | enrollments that have a due date posted |
| `tbd_or_unassigned` | enrollments with no date yet ("TBD" on the CMS list) |
| `posted_share_pct` | posted due dates as a share of enrollments |
| `cms_dataset_edition` | the CMS edition the row came from |

**Totals across the 15 states:** 1,837,311 enrollments, of which 181,678 have a posted due date.

**By state:**
- Texas has the highest share of posted due dates, at 15.6%: 34,795 of 222,775 enrollments.
- Next are Michigan (11.3%), North Carolina (11.2%) and Georgia (11.1%). Among the largest states, California is at 9.0%, Florida at 7.9% and New York at 7.9%.

## Why it matters
Under CMS rules (Program Integrity Manual, chapter 10, section 10.3.1.4), when an organization misses its group revalidation, the reassignments tied to it can be deactivated, and claims for that gap are not paid. The CMS list shows each due date in advance.

## Licence
This dataset is shared under CC BY 4.0: you may reuse it with attribution to Rōvn. The underlying CMS data is U.S. federal public data.

## How to cite
Rōvn (2026). Medicare revalidation due dates by state, CMS edition 2026-11-01. https://rovn.to/research/medicare-revalidation
