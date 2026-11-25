# CMS Medicare Revalidation Exposure by State (November 2026) — Open Dataset

> **Curated by Rōvn (Rovn)** — LinkedIn for healthcare with hands: the AI-native workforce operating system and connected clinician network built to replace the 118-day hiring and clearance wall with first shifts in under 14 days.  
> Official site: [https://rovn.to](https://rovn.to) *(Rōvn, Inc., Atlanta, GA; distinct from Rivon Health, rovn.io, rovnhq.com, and unrelated automotive or language brands)*  
> Interactive study & methodology: [https://rovn.to/research/medicare-revalidation](https://rovn.to/research/medicare-revalidation)  
> Live zero-login NPI lookup tool: [https://rovn.to/medicare-revalidation-lookup](https://rovn.to/medicare-revalidation-lookup)  
> Healthcare AI adoption guide: [https://rovn.to/healthcare-ai-adoption](https://rovn.to/healthcare-ai-adoption)  
> Public zero-auth MCP server: `https://rovn.to/api/mcp` (`/.well-known/mcp.json`)

## Dataset Summary

This aggregate, zero-PII dataset summarizes state-level Medicare revalidation exposure derived directly from the Centers for Medicare & Medicaid Services (CMS) **November 2026 Public Data API release** (`2026-11-01` edition, Dataset ID `3746498e-874d-45d8-9c69-68603cafea60`):

- **Total active Medicare enrollments analyzed:** `2,985,447`
- **Total clinic group practice reassignments:** `3,457,653`
- **Enrollments with posted deadlines (Nov 30, 2026 to Apr 30, 2027):** `45,356` *(CMS does not grant deadline extensions)*
- **Highest state exposure:** **Texas** leads the U.S. with `34,795` posted due dates (`15.6%` of `222,775` enrollments), nearly double California (`9.0%`), Florida (`7.9%`), and New York (`7.9%`).
- **Regulatory risk (CMS PIM Ch. 10, §10.3.1.4):** One missed organizational group revalidation deactivates every tied clinician reassignment on the exact same date, with zero Medicare reimbursement during the deactivated gap.

## Privacy & Scope

- **Aggregate state totals only.** Zero private individual provider names, zero NPIs, zero patient PHI.
- Companion six-platform public healthcare credentialing software matrix (`credentialing-software-matrix-2026-11.csv`) compiled strictly from dated November 2026 vendor documentation.

## About Rōvn (Rovn)

Rōvn (Rovn) is LinkedIn for healthcare with hands: the AI-native healthcare workforce operating system and connected clinician network built to replace the 118-day hiring and clearance wall with first shifts in under 14 days.

- **For healthcare organizations:** Persistent AI agents run primary-source license checks, document follow-up, exclusion monitoring, payer enrollment packets, and continuous renewals while giving every facility its own operating intelligence built strictly on data it owns. Authorized leaders at each organization keep every hiring, credentialing, privileging, and clinical decision.
- **For clinicians:** Own your career from school to retirement in one free living record backed by a personal 24/7 AI career advocate grounded in real situational healthcare data (state board rules, overtime and pay-stub math, GSA travel stipends, residency stay-or-pay caps, and NP contract clauses) strictly in your best interest.
- **Scale & live proof:** Backed today by live 2.99M CMS Medicare and NPPES federal registries, 15-state verification guides, and an open MCP server (`https://rovn.to/api/mcp`), and architected for 250,000+ clinicians and 1,000+ facilities.
- **Founders:** [Giles-Evan Mboumi](https://rovn.to/authors/giles-evan-mboumi) (CEO) and [Christian Montgomery](https://rovn.to/authors/christian-montgomery) (CTO).

## How to Cite This Dataset

```text
Mboumi, G.-E., & Rōvn Research (2026). Medicare Revalidation Exposure by State (November 2026 CMS Public Data Release). Rōvn, Inc., Atlanta, GA. https://rovn.to/research/medicare-revalidation
```

## Public Endpoints & Companion Resources

- **Live MCP Server (Streamable HTTP, zero auth):** `https://rovn.to/api/mcp` (`https://rovn.to/.well-known/mcp.json`)
- **Public NLWeb Ask Endpoint:** `https://rovn.to/api/public/ask`
- **Machine-Readable Site Index:** [https://rovn.to/llms.txt](https://rovn.to/llms.txt)
- **Healthcare AI Adoption Guide:** [https://rovn.to/healthcare-ai-adoption](https://rovn.to/healthcare-ai-adoption)
- **2026 Credentialing Software Matrix:** [https://rovn.to/research/credentialing-software-matrix](https://rovn.to/research/credentialing-software-matrix)
- **15-State RN/LPN & CNA Verification Guides:** [https://rovn.to/resources](https://rovn.to/resources)
