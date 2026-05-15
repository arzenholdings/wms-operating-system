# OPE Workspace Normalization Audit

Date: 2026-05-15  
Workspace: OpenClaw_Skream / OPE  
Scope: Audit and recommendations only. No projects, issues, labels, statuses, archives, or migrations were modified.

## Executive Summary

OPE is structurally close to a usable master operating workspace, but it still contains three visible "WRONG WORKSPACE" placeholder projects, several old Linear bootstrap issues, one stale Kinetic Moto AI project with only a canceled workspace-routing issue, and a few overlapping dashboard/command-center tasks.

The core operating system should stay lightweight: an executive operating layer, protected compliance/risk gates, business lane projects, and execution projects that feed the Weekly Operator Dashboard. The biggest cleanup need is not project deletion. It is classification, consolidation, and clearer hierarchy.

## Classification Legend

| Classification | Meaning |
| --- | --- |
| Core Active System | Central to the operating system and should remain visible in executive workflow. |
| Keep Active | Valid active work, but not necessarily a top-level operating pillar. |
| Merge Into Existing | Useful work that overlaps a stronger existing project or issue. |
| Archive Later | Candidate for archive after review and confirmation. |
| Historical Reference | Keep as record of past decision, setup, or deployment. |
| Placeholder/Test | Setup artifact, placeholder, or known wrong-workspace item. |
| Needs Manual Review | Needs human decision before consolidation or archive. |

## Project Audit

| Project | Classification | Recommendation |
| --- | --- | --- |
| Weekly Operator Dashboard | Core Active System | Protect. This is the executive weekly operating surface and should remain top-level. |
| Master Business Command Center | Core Active System | Keep as the business inventory and control framework, but avoid duplicating dashboard build tasks already covered by Weekly Operator Dashboard. |
| Compliance and Entity Cleanup | Core Active System | Protect. This is the legal/entity control layer. Consider sub-lanes for Cannabis Ops and Proletariat if they become active. |
| Workplace Management Solutions Repositioning | Core Active System | Keep. Consider renaming later to WMS Operating System and Client Delivery once positioning work is absorbed into the WMS framework. |
| Marketplace Profitability System | Core Active System | Keep. This is the marketplace buy/no-buy risk gate. |
| Supplier Acquisition Engine | Core Active System | Keep. This is the supplier intake and qualification pipeline. |
| ShopRite to Arzen Commerce Transition | Core Active System | Protect. This touches Amazon/Walmart account risk and should remain a controlled transition project. |
| Lightweight Arzen Commerce Website | Keep Active | Keep during build. Later fold into the Arzen Commerce growth lane or mark as complete. |
| The Driver Network MVP | Keep Active | Keep. This is an active product lane with compliance and beta milestones. |
| Kinetic Moto Isolation and Launch Readiness | Keep Active | Keep as the primary Kinetic Moto launch project. |
| Kinetic Moto AI Operations & Lead Automation | Needs Manual Review | Appears structurally confusing because the only visible issue is canceled. Merge active scope into Kinetic Moto Isolation if needed. |
| WRONG WORKSPACE - Distribution Expansion Plan | Placeholder/Test | Archive later after review. Covered by Supplier Acquisition Engine, Marketplace Profitability System, and Arzen Commerce growth work. |
| WRONG WORKSPACE - Vendor & Catalog Acquisition | Placeholder/Test | Archive later after review. Covered by Supplier Acquisition Engine. |
| WRONG WORKSPACE - Smoke Accessories Ecommerce Platform | Placeholder/Test | Archive later after review. Covered by Arzen Commerce website/marketplace work if still relevant. |

## Issue Audit

### Weekly Operator Dashboard

| Issue | Status | Classification | Recommendation |
| --- | --- | --- | --- |
| OPE-144 Dashboard View - Weekly Operator Dashboard | Todo | Core Active System | Keep as parent/dashboard view. |
| OPE-142 Create done this week section | Todo | Keep Active | Keep. |
| OPE-141 Create waiting on others section | Todo | Keep Active | Keep. |
| OPE-140 Create compliance deadlines section | Todo | Core Active System | Keep; feeds compliance control. |
| OPE-139 Create revenue opportunities section | Todo | Core Active System | Keep; feeds growth decisions. |
| OPE-138 Create supplier pipeline section | Todo | Keep Active | Keep; link to Supplier Acquisition Engine. |
| OPE-137 Create active projects by business section | Todo | Keep Active | Keep. |
| OPE-136 Create this week's top 5 priorities section | Todo | Core Active System | Keep as executive focus area. |
| OPE-135 Create critical blockers section | Todo | Core Active System | Keep as executive risk area. |

### Master Business Command Center

| Issue | Status | Classification | Recommendation |
| --- | --- | --- | --- |
| OPE-145 Create protected Arzen LLC monitoring lane | Todo | Core Active System | Protect. Use for Dragon Balm/protected seller account visibility. |
| OPE-143 Dashboard View - Master Business Command Center | Todo | Core Active System | Keep as command-center view. |
| OPE-61 Create monthly executive review checklist | Todo | Keep Active | Keep. |
| OPE-60 Create weekly review checklist | Todo | Merge Into Existing | Merge or link with Weekly Operator Dashboard review workflow. |
| OPE-59 Add business lane labels for each entity | Todo | Keep Active | Keep; some labels exist but lane coverage should be checked. |
| OPE-58 Add priority labels: Critical, High, Medium, Low | Todo | Historical Reference | Priority labels already exist. Mark complete or archive later after verification. |
| OPE-57 Add status labels: Not Started, In Progress, Blocked, Waiting, Complete | Todo | Historical Reference | Status labels already exist. Mark complete or archive later after verification. |
| OPE-56 Add progress indicators by business | Todo | Keep Active | Keep. |
| OPE-55 Create project dashboard design | Todo | Merge Into Existing | Merge with Weekly Operator Dashboard implementation. |
| OPE-54 Define active vs inactive vs protected entities | Todo | Keep Active | Keep. |
| OPE-53 Assign each entity a role | Todo | Keep Active | Keep. |
| OPE-52 Create business entity inventory table | Todo | Keep Active | Keep. |

### Compliance and Entity Cleanup

| Issue | Status | Classification | Recommendation |
| --- | --- | --- | --- |
| OPE-147 Create cannabis ops isolated reporting tracker | Todo | Needs Manual Review | Keep for now; may become Cannabis Ops sub-project if active. |
| OPE-146 Create Proletariat Products admin and billing tracker | Todo | Needs Manual Review | Keep for now; may become Proletariat admin/billing sub-project. |
| OPE-134 Decide keep / ignore / clean up / reinstate status | Todo | Core Active System | Keep. |
| OPE-133 Flag dissolved entities | Todo | Keep Active | Keep. |
| OPE-132 Flag delinquent entities | Todo | Core Active System | Keep. |
| OPE-131 Track Amazon/Walmart/website connections | Todo | Keep Active | Keep; link to Arzen Commerce transition. |
| OPE-130 Track bank account status | Todo | Keep Active | Keep. |
| OPE-129 Track registered agent | Todo | Keep Active | Keep. |
| OPE-128 Track annual report due date | Todo | Core Active System | Keep. |
| OPE-127 Track status | Todo | Keep Active | Keep. |
| OPE-126 Track UBI number | Todo | Keep Active | Keep. |
| OPE-125 Create entity compliance table | Todo | Core Active System | Keep. |

### Workplace Management Solutions Repositioning

| Issue | Status | Classification | Recommendation |
| --- | --- | --- | --- |
| OPE-148 Implement WMS operating system from customer journey framework | Backlog | Core Active System | Keep as WMS operating system anchor. |
| OPE-115 Create outbound lead list process | Todo | Keep Active | Keep. |
| OPE-114 Create LinkedIn positioning | Todo | Keep Active | Keep. |
| OPE-113 Create website update plan | Todo | Keep Active | Keep; link to any WMS site rebuild work. |
| OPE-112 Create first 3 service packages | Todo | Core Active System | Keep. |
| OPE-111 Create proposal template | Todo | Keep Active | Keep. |
| OPE-110 Create discovery call script | Todo | Keep Active | Keep. |
| OPE-109 Create client intake form | Todo | Core Active System | Keep. |
| OPE-108 Create GoHighLevel onboarding plan | Todo | Core Active System | Keep. |
| OPE-107 Create simple offer list | Todo | Keep Active | Keep. |
| OPE-106 Define WMS service menu | Todo | Core Active System | Keep. |

### The Driver Network MVP

| Issue | Status | Classification | Recommendation |
| --- | --- | --- | --- |
| OPE-49 Verify production Supabase persistence loop | Todo | Keep Active | Keep in active execution. |
| OPE-51 Plan market-ready Driver Network redesign | Backlog | Keep Active | Keep. |
| OPE-50 Later: clean up Codex Linear connector workspace routing | Backlog | Historical Reference | Keep as reference or archive later once routing is resolved. |
| OPE-6 Publish Driver Network code to GitHub and deploy preview | Done | Historical Reference | Keep as release record. |
| OPE-9 Define compliance posture for driver PII and payout data | Todo | Core Active System | Keep as protected compliance gate. |
| OPE-8 Research platform API and partner access requirements | Todo | Keep Active | Keep. |
| OPE-7 Lock prototype demo flow and screenshot pass | Todo | Keep Active | Keep in active execution. |
| OPE-15 Run private beta and decide next investment gate | Backlog | Keep Active | Keep. |
| OPE-14 Design private driver beta plan | Backlog | Keep Active | Keep. |
| OPE-13 Assess iOS/TestFlight wrapper after backend is stable | Backlog | Keep Active | Keep. |
| OPE-12 Prepare PWA install path before native iOS build | Backlog | Keep Active | Keep. |
| OPE-11 Implement auth and secure driver profile storage | Backlog | Keep Active | Keep. |
| OPE-10 Select backend stack and production data model | Backlog | Keep Active | Keep. |

### Kinetic Moto Isolation and Launch Readiness

| Issue | Status | Classification | Recommendation |
| --- | --- | --- | --- |
| OPE-124 Create weekly status update | Todo | Keep Active | Keep. |
| OPE-123 Create lead capture form | Todo | Merge Into Existing | Keep if website-specific; otherwise merge into Kinetic Moto AI/lead automation scope. |
| OPE-122 Create financing page checklist | Todo | Keep Active | Keep. |
| OPE-121 Create launch checklist | Todo | Core Active System | Keep as Kinetic launch gate. |
| OPE-120 Create supplier list | Todo | Keep Active | Keep as Kinetic-specific supplier list. |
| OPE-119 Identify top 5 bike models | Todo | Keep Active | Keep. |
| OPE-118 Review current product catalog | Todo | Keep Active | Keep. |
| OPE-117 Confirm domain and deployment | Todo | Keep Active | Keep. |
| OPE-116 Confirm current website status | Todo | Keep Active | Keep. |

### Kinetic Moto AI Operations & Lead Automation

| Issue | Status | Classification | Recommendation |
| --- | --- | --- | --- |
| OPE-5 Apply Supabase migrations and verify Phase 3 lead flow | Canceled | Archive Later | Archive after review. It appears to be a stale workspace-routing artifact, not active OPE execution. |

### Supplier Acquisition Engine

| Issue | Status | Classification | Recommendation |
| --- | --- | --- | --- |
| OPE-95 Create supplier scoring model | Todo | Core Active System | Keep. |
| OPE-94 Create SKU sheet upload process | Todo | Keep Active | Keep. |
| OPE-93 Create margin analysis intake form | Todo | Merge Into Existing | Link with Marketplace Profitability System so margin logic is not duplicated. |
| OPE-92 Create scam-risk checklist | Todo | Core Active System | Keep as supplier risk gate. |
| OPE-91 Create document storage structure | Todo | Keep Active | Keep. |
| OPE-90 Create reseller certificate packet | Todo | Keep Active | Keep. |
| OPE-89 Create vendor application packet | Todo | Keep Active | Keep. |
| OPE-88 Create phone script | Todo | Keep Active | Keep. |
| OPE-87 Create supplier outreach email templates | Todo | Keep Active | Keep. |
| OPE-86 Create approved / rejected / follow-up statuses | Todo | Keep Active | Keep. |
| OPE-85 Define supplier qualification checklist | Todo | Core Active System | Keep. |
| OPE-84 Create supplier CRM pipeline | Todo | Core Active System | Keep. |

### Marketplace Profitability System

| Issue | Status | Classification | Recommendation |
| --- | --- | --- | --- |
| OPE-105 Create pass/fail rules | Todo | Keep Active | Keep. |
| OPE-104 Document every product decision before inventory purchase | Todo | Core Active System | Protect as buy/no-buy gate. |
| OPE-103 Create approved buy list output | Todo | Keep Active | Keep. |
| OPE-102 Create no-buy rules | Todo | Core Active System | Protect as marketplace risk gate. |
| OPE-101 Create test order rules | Todo | Keep Active | Keep. |
| OPE-100 Create replenishment rules | Todo | Keep Active | Keep. |
| OPE-99 Create minimum margin thresholds | Todo | Core Active System | Keep. |
| OPE-98 Create product risk scoring | Todo | Core Active System | Keep. |
| OPE-97 Add fields: SKU, UPC, ASIN, cost, shipping, FBA fee, referral fee, storage estimate, sell price, net profit, ROI, margin, sales rank, competition, brand risk, gating status | Todo | Keep Active | Keep. |
| OPE-96 Define product intake spreadsheet | Todo | Core Active System | Keep. |

### ShopRite to Arzen Commerce Transition

| Issue | Status | Classification | Recommendation |
| --- | --- | --- | --- |
| OPE-73 Create account risk checklist before making changes | Todo | Core Active System | Protect as seller account risk gate. |
| OPE-72 Reactivate or review Walmart seller account | Todo | Keep Active | Keep. |
| OPE-71 Update seller account only after all documents match | Todo | Core Active System | Protect. |
| OPE-70 Create simple brand identity | Todo | Keep Active | Keep; link to website brand placeholder if needed. |
| OPE-69 Set up Microsoft 365 email aliases | Todo | Keep Active | Keep; link with website email task. |
| OPE-68 Decide operating name: Arzen Commerce, Arzen Supply, or Arzen Marketplace | Todo | Keep Active | Keep. |
| OPE-67 Create safe transition checklist | Todo | Core Active System | Protect. |
| OPE-66 Research Amazon rules for account name / legal entity / display name updates | Todo | Core Active System | Protect. |
| OPE-65 Identify current legal name, display name, bank account, tax info, and storefront name | Todo | Core Active System | Protect. |
| OPE-64 Confirm Amazon Seller Central account status | Todo | Core Active System | Protect. |
| OPE-63 Secure domain | Todo | Keep Active | Keep. |
| OPE-62 Review current ShopRite LLC status | Todo | Core Active System | Keep. |

### Lightweight Arzen Commerce Website

| Issue | Status | Classification | Recommendation |
| --- | --- | --- | --- |
| OPE-83 Add basic SEO metadata and compliance footer | Todo | Keep Active | Keep. |
| OPE-82 Connect domain | Todo | Keep Active | Keep. |
| OPE-81 Deploy to Vercel | Todo | Keep Active | Keep. |
| OPE-80 Add Microsoft 365 email | Todo | Merge Into Existing | Link or merge with OPE-69. |
| OPE-79 Create contact form | Todo | Keep Active | Keep. |
| OPE-78 Create supplier partnerships page | Todo | Keep Active | Keep. |
| OPE-77 Create homepage | Todo | Keep Active | Keep. |
| OPE-76 Create brand placeholder | Todo | Merge Into Existing | Link or merge with OPE-70. |
| OPE-75 Create Next.js app | Todo | Keep Active | Keep. |
| OPE-74 Create repo | Todo | Keep Active | Keep. |

### WRONG WORKSPACE - Distribution Expansion Plan

| Issue | Status | Classification | Recommendation |
| --- | --- | --- | --- |
| OPE-48 Exclusive vendor strategy | Canceled | Placeholder/Test | Archive later after review. |
| OPE-47 Regional sales rep planning | Canceled | Placeholder/Test | Archive later after review. |
| OPE-46 White-label roadmap | Canceled | Placeholder/Test | Archive later after review. |
| OPE-45 ACH/net terms planning | Canceled | Placeholder/Test | Archive later after review. |
| OPE-44 Freight workflow planning | Canceled | Placeholder/Test | Archive later after review. |
| OPE-43 Barcode/SKU standards | Canceled | Placeholder/Test | Archive later after review. |
| OPE-42 Inventory software research | Canceled | Placeholder/Test | Archive later after review. |
| OPE-41 Warehouse planning | Canceled | Placeholder/Test | Archive later after review. |

### WRONG WORKSPACE - Vendor & Catalog Acquisition

| Issue | Status | Classification | Recommendation |
| --- | --- | --- | --- |
| OPE-40 Create pricing rules framework | Canceled | Placeholder/Test | Archive later after review. |
| OPE-38 Create category mapping system | Canceled | Placeholder/Test | Archive later after review. |
| OPE-39 Build product image collection process | Canceled | Placeholder/Test | Archive later after review. |
| OPE-37 Build CSV normalization workflow | Canceled | Placeholder/Test | Archive later after review. |
| OPE-36 Determine dropship vs inventory logic | Canceled | Placeholder/Test | Archive later after review. |
| OPE-35 Create MAP pricing workflow | Canceled | Placeholder/Test | Archive later after review. |
| OPE-34 Build vendor intake spreadsheet | Canceled | Placeholder/Test | Archive later after review. |
| OPE-32 Gather vendor relationships | Canceled | Placeholder/Test | Archive later after review. |

### WRONG WORKSPACE - Smoke Accessories Ecommerce Platform

| Issue | Status | Classification | Recommendation |
| --- | --- | --- | --- |
| OPE-33 Create mobile responsive layout | Canceled | Placeholder/Test | Archive later after review. |
| OPE-31 Configure Vercel deployment | Canceled | Placeholder/Test | Archive later after review. |
| OPE-30 Configure SEO metadata structure | Canceled | Placeholder/Test | Archive later after review. |
| OPE-29 Create CSV product import workflow | Canceled | Placeholder/Test | Archive later after review. |
| OPE-28 Create admin dashboard placeholder | Canceled | Placeholder/Test | Archive later after review. |
| OPE-27 Create vendor onboarding form | Canceled | Placeholder/Test | Archive later after review. |
| OPE-26 Create wholesale login structure | Canceled | Placeholder/Test | Archive later after review. |
| OPE-25 Create dealer registration page | Canceled | Placeholder/Test | Archive later after review. |
| OPE-24 Create product detail page structure | Canceled | Placeholder/Test | Archive later after review. |
| OPE-23 Create category page structure | Canceled | Placeholder/Test | Archive later after review. |
| OPE-22 Create homepage | Canceled | Placeholder/Test | Archive later after review. |
| OPE-21 Configure Supabase | Canceled | Placeholder/Test | Archive later after review. |
| OPE-20 Configure shadcn/ui | Canceled | Placeholder/Test | Archive later after review. |
| OPE-19 Configure Tailwind | Canceled | Placeholder/Test | Archive later after review. |
| OPE-18 Initialize Next.js app | Canceled | Placeholder/Test | Archive later after review. |
| OPE-17 Create GitHub repository | Canceled | Placeholder/Test | Archive later after review. |
| OPE-16 Choose company/domain name | Canceled | Placeholder/Test | Archive later after review. |

### Orphaned / Bootstrap Issues

These issues appeared outside the current project structure and look like initial Linear setup artifacts.

| Issue | Classification | Recommendation |
| --- | --- | --- |
| OPE-1 Get familiar with Linear | Placeholder/Test | Archive later after review. |
| OPE-2 Set up your teams | Placeholder/Test | Archive later after review. |
| OPE-3 Connect your tools | Placeholder/Test | Archive later after review. |
| OPE-4 Import your data | Placeholder/Test | Archive later after review. |

## Duplicate and Overlap Findings

| Area | Finding | Recommendation |
| --- | --- | --- |
| Dashboard layer | Master Business Command Center and Weekly Operator Dashboard overlap on dashboard design/review checklist work. | Keep both top-level, but make Weekly Operator Dashboard the weekly execution surface and Master Business Command Center the business inventory/control surface. |
| Kinetic Moto | Kinetic Moto AI Operations & Lead Automation overlaps Kinetic Moto Isolation and Launch Readiness and has only a canceled visible issue. | Move any valid lead automation scope into Kinetic Moto Isolation and archive the stale project later if no active work remains. |
| WMS | WMS Repositioning now overlaps the WMS operating system architecture. | Keep it, but rename or reframe later around WMS Operating System and Client Delivery. |
| Supplier/distribution | WRONG WORKSPACE distribution/vendor projects duplicate Supplier Acquisition Engine and Marketplace Profitability System. | Treat wrong-workspace projects as covered by OPE and archive later after review. |
| Microsoft 365 | OPE-69 and OPE-80 both cover email setup. | Link or merge so Arzen Commerce transition owns the decision and website owns implementation only if needed. |
| Brand placeholder | OPE-70 and OPE-76 overlap. | Keep OPE-70 as brand decision; make OPE-76 website implementation or merge. |
| Margin intake | OPE-93 overlaps Marketplace Profitability System. | Supplier pipeline should collect inputs; Marketplace Profitability should own scoring rules. |

## Empty, Stale, and Confusing Items

| Item | Category | Recommendation |
| --- | --- | --- |
| Kinetic Moto AI Operations & Lead Automation | Empty/structurally confusing active project | Needs manual review. If no hidden active issues exist, archive later after moving any valid scope. |
| WRONG WORKSPACE projects | Placeholder/test and wrong-workspace artifacts | Archive later after review. Do not delete. |
| OPE-1 through OPE-4 | Old Linear bootstrap artifacts | Archive later after review. |
| OPE-5 | Stale AI/connector/workspace artifact | Archive later after review. |
| OPE-57 and OPE-58 | Already represented elsewhere | Verify labels exist, then mark done or archive later. |

## Missing Executive-Level Initiatives

These should exist conceptually in OPE as initiatives, views, or project groupings. They do not need heavy process.

| Missing Initiative | Purpose |
| --- | --- |
| Executive Operating System | Weekly dashboard, command center, active priorities, blockers, and review cadence. |
| Entity and Compliance Control | Entity status, deadlines, protected accounts, risk gates, and cleanup decisions. |
| WMS Operating System and Client Delivery | Source-of-truth WMS framework, onboarding, CRM stages, SOPs, and reusable delivery. |
| Arzen Commerce Marketplace Growth | ShopRite transition, protected Arzen LLC seller account monitoring, supplier engine, website, and marketplace profitability. |
| Supplier and Catalog Intake | Supplier pipeline, vendor qualification, reseller packet, SKU ingestion, and scam-risk review. |
| Kinetic Moto Launch | Website, catalog, financing, lead capture, supplier list, and launch readiness. |
| Driver Network Product | MVP, backend, compliance, beta, and investment gate. |
| Admin, Billing, and Special Compliance | Proletariat admin/billing and Cannabis Ops isolated reporting if still active. |

## Recommended Final OPE Project Structure

Keep the final list small and operational:

| Final Project | Source / Notes |
| --- | --- |
| Weekly Operator Dashboard | Keep current project. |
| Master Business Command Center | Keep current project; remove dashboard duplication over time. |
| Compliance and Entity Cleanup | Keep current project. |
| WMS Operating System and Client Delivery | Rename or evolve from Workplace Management Solutions Repositioning. |
| Arzen Commerce Transition and Marketplace Growth | Use ShopRite to Arzen Commerce Transition as protected transition anchor; link website and marketplace work. |
| Supplier Acquisition Engine | Keep current project. |
| Marketplace Profitability System | Keep current project. |
| Kinetic Moto Launch Readiness | Keep Kinetic Moto Isolation and Launch Readiness as the main project. |
| Driver Network MVP | Keep current project. |
| Proletariat Admin and Billing | Create only if Proletariat work becomes active beyond tracker issue OPE-146. |
| Cannabis Ops Isolated Reporting | Create only if Cannabis Ops requires recurring reporting beyond tracker issue OPE-147. |

Projects not recommended for the final active list:

| Project | Reason |
| --- | --- |
| Kinetic Moto AI Operations & Lead Automation | Merge active scope into Kinetic Moto Launch Readiness; archive later if empty. |
| WRONG WORKSPACE - Distribution Expansion Plan | Covered by OPE supplier/marketplace projects. |
| WRONG WORKSPACE - Vendor & Catalog Acquisition | Covered by Supplier Acquisition Engine. |
| WRONG WORKSPACE - Smoke Accessories Ecommerce Platform | Covered by Arzen Commerce website/marketplace projects. |

## Recommended Initiative Hierarchy

| Initiative | Projects |
| --- | --- |
| Executive Operating System | Weekly Operator Dashboard; Master Business Command Center |
| Entity and Compliance Control | Compliance and Entity Cleanup; protected Arzen LLC monitoring lane |
| WMS Operating System and Client Delivery | Workplace Management Solutions Repositioning; WMS framework implementation |
| Arzen Commerce Marketplace Growth | ShopRite to Arzen Commerce Transition; Lightweight Arzen Commerce Website; Marketplace Profitability System |
| Supplier and Catalog Intake | Supplier Acquisition Engine; supplier-related website pages |
| Kinetic Moto Launch | Kinetic Moto Isolation and Launch Readiness; valid lead automation tasks if retained |
| Driver Network Product | The Driver Network MVP |
| Admin and Special Compliance | Proletariat admin/billing tracker; Cannabis Ops isolated reporting tracker |

## Recommended Archive Candidates

Do not archive automatically. Review first.

| Candidate | Reason |
| --- | --- |
| WRONG WORKSPACE - Distribution Expansion Plan | Canceled placeholder project already covered by OPE. |
| WRONG WORKSPACE - Vendor & Catalog Acquisition | Canceled placeholder project already covered by OPE. |
| WRONG WORKSPACE - Smoke Accessories Ecommerce Platform | Canceled placeholder project already covered by OPE. |
| OPE-1 through OPE-4 | Linear bootstrap artifacts. |
| OPE-5 | Canceled workspace-routing/stale AI artifact. |
| Kinetic Moto AI Operations & Lead Automation | Archive later if no hidden active scope remains. |
| OPE-57 and OPE-58 | Label setup tasks appear already represented; verify first. |

## Do Not Touch / Protected Projects and Issues

| Item | Reason |
| --- | --- |
| ShopRite to Arzen Commerce Transition | Contains Amazon/Walmart seller account transition risks. |
| OPE-64, OPE-65, OPE-66, OPE-67, OPE-71, OPE-73 | Protected account and compliance gates. |
| Marketplace Profitability System | Controls buy/no-buy decisions before inventory spend. |
| OPE-102 and OPE-104 | Product risk and purchase documentation gates. |
| Compliance and Entity Cleanup | Legal/entity governance layer. |
| OPE-125, OPE-128, OPE-132, OPE-134 | Entity compliance control tasks. |
| The Driver Network MVP compliance tasks | PII, payout, backend, and beta risk. |
| Weekly Operator Dashboard | Executive operating layer. |

## Recommended Active Execution List

Top active execution items for the next operating cycle:

1. OPE-136 - Create this week's top 5 priorities section.
2. OPE-135 - Create critical blockers section.
3. OPE-148 - Implement WMS operating system from customer journey framework.
4. OPE-125 - Create entity compliance table.
5. OPE-134 - Decide keep / ignore / clean up / reinstate status.
6. OPE-64 through OPE-67 - Confirm Amazon status and transition rules before account changes.
7. OPE-84 and OPE-85 - Create supplier CRM pipeline and qualification checklist.
8. OPE-96, OPE-99, OPE-102, OPE-104 - Build marketplace profitability gates.
9. OPE-116 through OPE-121 - Confirm Kinetic Moto state and launch checklist.
10. OPE-7, OPE-9, OPE-49 - Driver Network demo, compliance posture, and Supabase persistence.

## Recommended Operational Dashboard Groupings

| Grouping | Purpose |
| --- | --- |
| Critical Blockers | Items blocking revenue, compliance, deployment, or protected accounts. |
| This Week's Top 5 Priorities | Executive focus list. |
| Active Projects by Business Lane | WMS, Arzen Commerce, Arzen LLC, Kinetic Moto, Driver Network, Cannabis Ops, Proletariat. |
| Protected Accounts and Risk Gates | Amazon/Walmart, Arzen LLC, compliance deadlines, buy/no-buy gates. |
| Compliance Deadlines | Entity filings, annual reports, registered agent, bank/account status. |
| Revenue Opportunities | WMS offers, supplier pipeline, marketplace growth, Kinetic Moto leads. |
| Supplier Pipeline | Outreach, qualification, document packet, SKU upload, scoring. |
| Waiting on Others | External dependencies and blocked handoffs. |
| Done This Week | Completed execution record. |
| Archive Review Queue | Wrong-workspace, bootstrap, duplicate, and superseded artifacts. |
| Manual Review Queue | Kinetic Moto AI Operations, Cannabis Ops, Proletariat, label setup remnants. |

## Recommended Labels

Existing labels cover most basic needs. Add only lightweight labels that improve routing:

| Label | Why |
| --- | --- |
| Business: Driver Network | Driver Network is an active lane but should be explicitly labelable. |
| Business: Executive Ops | For dashboard, command center, and review cadence work. |
| Business: OpenClaw / Workspace Admin | For connector/routing/bootstrap artifacts. |
| Type: Risk Gate | For protected account, compliance, and buy/no-buy blockers. |
| Type: Documentation | For SOP/framework deliverables. |
| Type: Deployment | For GitHub/Vercel/site release tasks. |
| Type: Research | For API, regulatory, and account-rule research. |
| Type: Dashboard | For dashboard view and reporting work. |
| Status: Superseded | For valid old work replaced by a stronger OPE item. |
| Status: Protected | For issues that should not be casually moved, renamed, or closed. |
| Status: Needs Manual Review | For uncertain items before archive/merge. |
| Archive Candidate | For cleanup queue without deleting or archiving immediately. |

## Projects That Should Become Sub-Projects or Milestones

| Current Item | Recommended Shape |
| --- | --- |
| Lightweight Arzen Commerce Website | Keep during build; later make it a milestone under Arzen Commerce Marketplace Growth. |
| Kinetic Moto AI Operations & Lead Automation | Convert valid active work into milestones under Kinetic Moto Launch Readiness. |
| Master Business Command Center dashboard build tasks | Keep command center as inventory/control; move weekly dashboard implementation to Weekly Operator Dashboard. |
| Proletariat Products admin and billing tracker | If recurring, create a small Proletariat Admin and Billing project; otherwise keep as Compliance issue. |
| Cannabis Ops isolated reporting tracker | If recurring, create a small Cannabis Ops reporting project; otherwise keep as Compliance issue. |
| WMS website update plan | Keep inside WMS unless it becomes a dedicated build with repo/deployment work. |

## Normalization Sequence

Recommended order after review:

1. Tag archive candidates instead of archiving immediately.
2. Confirm whether Kinetic Moto AI Operations has hidden or external active scope.
3. Mark wrong-workspace projects as covered by OPE.
4. Link overlapping issues instead of duplicating work.
5. Convert recurring business lanes into projects only when they have active recurring execution.
6. Build dashboard groupings before any archive pass so cleanup does not remove useful visibility.
7. Archive only after a second review pass.

## Final Recommendation

OPE should remain the master workspace. The workspace does not need a complex agency-style structure. It needs a clean operating hierarchy:

- executive dashboard and command center,
- protected compliance and account risk gates,
- business lane execution projects,
- supplier/marketplace engines,
- WMS operating system delivery,
- small archive/manual-review queues for artifacts.

The final active OPE structure should protect the Weekly Operator Dashboard, Master Business Command Center, Compliance and Entity Cleanup, WMS Operating System, Arzen Commerce transition, Supplier Acquisition Engine, Marketplace Profitability System, Kinetic Moto, and Driver Network. Wrong-workspace and bootstrap artifacts should be retained only until reviewed, then archived later.
