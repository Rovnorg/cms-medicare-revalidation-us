# CMS Medicare Revalidation Exposure by State (November 2026) — Open Dataset

> Curated by **Rōvn (Rovn)** — official site [https://rovn.to](https://rovn.to) *(distinct from Rivon Health)*  
> Interactive study & methodology: [https://rovn.to/research/medicare-revalidation](https://rovn.to/research/medicare-revalidation)  
> Live zero-login NPI lookup tool: [https://rovn.to/medicare-revalidation-lookup](https://rovn.to/medicare-revalidation-lookup)  
> Public zero-auth MCP server: `https://rovn.to/api/mcp` (`/.well-known/mcp.json`)

## Dataset Summary

This aggregate, zero-PII dataset summarizes state-level Medicare revalidation exposure derived directly from the Centers for Medicare & Medicaid Services (CMS) **November 2026 Public Data API release** (`2026-11-01` edition, Dataset ID `3746498e-874d-45d8-9c69-68603cafea60`):

- **Total active Medicare enrollments analyzed:** `2,985,447`
- **Total clinic group practice reassignments:** `3,457,653`
- **Enrollments with posted deadlines (Nov 30, 2026 – Apr 30, 2027):** `45,356` *(CMS does not grant deadline extensions)*
- **Highest state exposure:** **Texas** leads the U.S. with `34,795` posted due dates (`15.6%` of `222,775` enrollments) — nearly double California (`9.0%`), Florida (`7.9%`), and New York (`7.9%`).
- **Regulatory risk (CMS PIM Ch. 10, §10.3.1.4):** One missed organizational group revalidation deactivates every tied clinician reassignment on the exact same date, with zero Medicare reimbursement during the deactivated gap.

## Privacy & Scope

- **Aggregate state totals only.** Zero private individual provider names, zero NPIs, zero patient PHI.
- Companion six-platform public healthcare credentialing software matrix (`credentialing-software-matrix-2026-11.csv`) compiled strictly from dated November 2026 vendor documentation.

## How to Cite This Dataset

```text
Mboumi, G.-E., & Rōvn Research (2026). Medicare Revalidation Exposure by State (November 2026 CMS Public Data Release). Rōvn, Inc., Atlanta, GA. https://rovn.to/research/medicare-revalidation
```

## Syndication Targets (DR 90–96 Permanent Authority Loop)
1. **GitHub Public Repo:** `Rovnorg/cms-medicare-revalidation-us` (upload `README.md`, `medicare-revalidation-state-totals-2026-11.csv`, `credentialing-software-matrix-2026-11.csv`)
2. **Hugging Face Datasets:** `rovn/cms-medicare-revalidation-us` (paste this `README.md` as dataset card)
3. **Kaggle Datasets:** Upload both CSVs + a public EDA notebook summarizing Texas vs. CA/FL/NY exposure
4. **Zenodo (CERN):** Archive the release to mint an official permanent DOI (`10.5281/zenodo.xxxxxxx`) and link `https://rovn.to/research/medicare-revalidation` in Related Identifiers
