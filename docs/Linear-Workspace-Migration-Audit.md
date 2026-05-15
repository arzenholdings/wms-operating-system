# Linear Workspace Migration Audit

Created: 2026-05-15

## Purpose

Audit the older `Skream / SKR` project list against the newer `OpenClaw_Skream / OPE` project list and recommend which older projects should be copied, recreated, linked, archived later, or ignored.

## Ground Rules

- `OPE` is the master Linear team/workspace going forward.
- No projects were deleted.
- No projects were moved.
- No SKR projects were copied or recreated.
- No OPE project data was changed.
- Duplicate SKR projects are marked as covered by OPE where applicable.

## Access Note

The Linear connector currently exposes only one team:

| Team | Key | Visibility |
|---|---|---|
| OpenClaw_Skream | OPE | Visible through connector |

Direct connector queries for `SKR` returned no visible projects, and full-text project searches only returned OPE-visible projects. Therefore, the SKR side of this audit uses the SKR project list supplied by Ben as the source inventory.

## Current OPE Project List

These projects are visible in OPE and should be treated as the current master list:

| OPE project | Status / note |
|---|---|
| Weekly Operator Dashboard | Master weekly execution dashboard. |
| Compliance and Entity Cleanup | Entity, compliance, renewal, registered-agent, and cleanup tracker. |
| Kinetic Moto Isolation and Launch Readiness | Kinetic Moto launch and separation roadmap. |
| Workplace Management Solutions Repositioning | WMS service identity and operating direction. |
| Marketplace Profitability System | Amazon/Walmart buy-watch-reject and product analysis system. |
| Supplier Acquisition Engine | Supplier targeting, vetting, outreach, documents, catalog, and onboarding. |
| Lightweight Arzen Commerce Website | Supplier-facing credibility website. |
| ShopRite to Arzen Commerce Transition | Transition ShopRite into the ecommerce/distribution growth vehicle. |
| Master Business Command Center | Executive operating view across entities and priorities. |
| The Driver Network MVP | Canonical Driver Network project in OPE. |
| Kinetic Moto AI Operations & Lead Automation | AI workflows and lead automation for Kinetic Moto/WMS validation. |
| WRONG WORKSPACE - Distribution Expansion Plan | Canceled placeholder; do not use for execution. |
| WRONG WORKSPACE - Vendor & Catalog Acquisition | Canceled placeholder; do not use for execution. |
| WRONG WORKSPACE - Smoke Accessories Ecommerce Platform | Canceled placeholder; do not use for execution. |

## SKR Project Recommendations

| SKR project | Recommendation | OPE coverage / action | Rationale |
|---|---|---|---|
| Distribution Expansion Plan | Already covered in OPE | Covered by `ShopRite to Arzen Commerce Transition`, `Supplier Acquisition Engine`, and `Marketplace Profitability System`. Mark old SKR project as `covered by OPE`; archive later after review. | OPE now separates entity transition, supplier engine, and profitability system more cleanly than the older broad distribution project. |
| Vendor & Catalog Acquisition | Already covered in OPE | Covered by `Supplier Acquisition Engine`. Mark old SKR project as `covered by OPE`; archive later after review. | Supplier statuses, documents, catalog receipt, pricing analysis, and test orders are already represented in the OPE supplier system. |
| Smoke Accessories Ecommerce Platform | Needs manual review | Partially covered by `Lightweight Arzen Commerce Website`, `ShopRite to Arzen Commerce Transition`, and `Marketplace Profitability System`; may also belong under a future `Cannabis Ops` project if still active. | Do not recreate as a generic ecommerce platform without confirming whether the smoke/cannabis vertical is still an active lane. |
| The Driver Network MVP | Already covered in OPE | Covered by exact OPE project `The Driver Network MVP`. Mark old SKR project as `covered by OPE`; archive later after review. | OPE has the canonical project with live app, GitHub, and Vercel links. |
| Federal Award Stock Alert Scanner | Copy to OPE | Create an OPE project only if the scanner is still active; otherwise add it as a linked reference under `Master Business Command Center`. | This appears to be a distinct working product/repo and is not currently represented in the OPE project list. |
| Workplace Management Solutions - GoDaddy -> Vercel Rebuild | Copy to OPE | Prefer creating issues/milestones under `Workplace Management Solutions Repositioning`; create a separate OPE project only if it has an independent launch deadline. | WMS repositioning exists, but the website rebuild itself is not explicitly represented. Avoid duplicating unless the web rebuild needs project-level tracking. |
| MLO License Completion - WA | Copy to OPE | Create as an OPE compliance/legal project or milestone under `Compliance and Entity Cleanup`. | Licensing deadlines and compliance status are high-risk enough to preserve in the master workspace if still active. |
| Estate Plan Execution - Dylan Trust | Keep in SKR only | Do not copy unless Ben wants OPE to include personal/legal estate administration. | This does not appear to be part of the operating architecture for WMS/Arzen business execution. |
| Euphorium Competitive Analysis (YourWeedData) | Keep in SKR only | Keep as historical research unless it feeds active `Cannabis Ops`. Archive later after confirming artifacts are saved. | Looks like a research/deck artifact, not an ongoing operating project. |
| Kinetic-Moto.com Site Build Project | Already covered in OPE | Covered by `Kinetic Moto Isolation and Launch Readiness`; related automation belongs under `Kinetic Moto AI Operations & Lead Automation`. Mark old SKR project as `covered by OPE`; archive later after review. | OPE has cleaner separation between site/launch readiness and AI/lead automation. |
| Darrington Mayor LCB Property Approval Packet | Needs manual review | If active, create OPE project `Cannabis Ops - Darrington LCB Approval Packet` or track under `Compliance and Entity Cleanup`. | Potentially legal/regulatory and property-specific; should not be silently merged into a general project. |
| DopeTech App Roll Out | Needs manual review | If active, create a focused OPE project; if dormant, keep in SKR and archive later. | Not currently represented in OPE and needs business priority confirmation before adding. |

## Missing High-Value OPE Projects

Recommended additions only after review:

| Missing project | Recommended shape |
|---|---|
| Federal Award Stock Alert Scanner | OPE project if active product; otherwise linked reference in Master Business Command Center. |
| WMS Website Rebuild / GoDaddy to Vercel | Milestone/issues inside `Workplace Management Solutions Repositioning`; separate project only if independently scheduled. |
| MLO License Completion - WA | OPE compliance project or milestone under `Compliance and Entity Cleanup`. |
| Cannabis Ops - Darrington LCB Approval Packet | Manual-review project if still active; compliance-sensitive. |
| DopeTech App Roll Out | Manual-review project if still active product/business lane. |
| Cannabis Ops Operating Lane | Lightweight umbrella only if cannabis-related work remains active beyond one packet/research artifact. |

## Duplicate or Confusing Projects

| Item | Issue | Recommendation |
|---|---|---|
| `WRONG WORKSPACE - Distribution Expansion Plan` | Canceled placeholder exists in OPE and can confuse the master list. | Keep for now; archive later after this audit is reviewed. Do not use for execution. |
| `WRONG WORKSPACE - Vendor & Catalog Acquisition` | Canceled placeholder exists in OPE and can confuse the master list. | Keep for now; archive later after this audit is reviewed. Do not use for execution. |
| `WRONG WORKSPACE - Smoke Accessories Ecommerce Platform` | Canceled placeholder exists in OPE and can confuse the master list. | Keep for now; archive later after this audit is reviewed. Do not use for execution. |
| `Weekly Operator Dashboard` vs `Master Business Command Center` | Names overlap in dashboard/command-center concept. | Keep both, but define boundaries: Weekly Dashboard is the weekly execution UI; Master Command Center is the cross-entity operating model. |
| `Kinetic Moto Isolation and Launch Readiness` vs `Kinetic Moto AI Operations & Lead Automation` | Both mention Kinetic Moto. | Keep both, but define boundaries: launch/site/business readiness vs AI/lead automation workflows. |
| `Workplace Management Solutions Repositioning` vs WMS operating-system artifacts | WMS now has both a Linear project and a GitHub operating-system repo. | Keep Linear for implementation; keep GitHub for source-of-truth docs. Consider renaming Linear project later to `WMS Operating System & Repositioning`. |

## Recommended Clean Final OPE Project List

Keep these active/canonical:

1. Weekly Operator Dashboard
2. Master Business Command Center
3. Compliance and Entity Cleanup
4. Workplace Management Solutions Repositioning
5. ShopRite to Arzen Commerce Transition
6. Lightweight Arzen Commerce Website
7. Supplier Acquisition Engine
8. Marketplace Profitability System
9. The Driver Network MVP
10. Kinetic Moto Isolation and Launch Readiness
11. Kinetic Moto AI Operations & Lead Automation

Add after review if still active:

12. Federal Award Stock Alert Scanner
13. WMS Website Rebuild / GoDaddy to Vercel
14. MLO License Completion - WA
15. Cannabis Ops - Darrington LCB Approval Packet
16. DopeTech App Roll Out
17. Cannabis Ops Operating Lane

Archive later after review:

18. WRONG WORKSPACE - Distribution Expansion Plan
19. WRONG WORKSPACE - Vendor & Catalog Acquisition
20. WRONG WORKSPACE - Smoke Accessories Ecommerce Platform

Do not copy unless explicitly approved:

- Estate Plan Execution - Dylan Trust
- Euphorium Competitive Analysis (YourWeedData)

## Recommended Migration Sequence

1. Review this audit and approve which SKR items should become OPE projects.
2. Mark old SKR duplicates as `covered by OPE` in their descriptions or status notes.
3. Create only the missing high-value OPE projects that are still active.
4. Link old SKR project URLs in the new OPE project descriptions when useful.
5. Archive canceled OPE placeholders only after the clean list is confirmed.
6. Leave historical research/legal-personal work in SKR unless it becomes active business execution.

## No Migration Performed

This report is recommendation-only. No Linear projects were moved, copied, archived, deleted, or modified.

