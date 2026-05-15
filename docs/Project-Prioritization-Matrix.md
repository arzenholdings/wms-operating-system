# Project Prioritization Matrix

Date: 2026-05-15

Workspace: OpenClaw_Skream / OPE

## Purpose

This matrix adds operational prioritization metadata to the OPE operating system so projects can be ranked by execution difficulty, expected duration, and revenue timing.

The intended project-level label groups are:

| Group | Labels |
| --- | --- |
| Difficulty | Difficulty: Easy, Difficulty: Medium, Difficulty: Hard, Difficulty: Extreme |
| Duration | Duration: Short, Duration: Medium, Duration: Long |
| Revenue | Revenue: Immediate, Revenue: Delayed, Revenue: Strategic |

## Connector Note

The Linear connector available in this session can create workspace issue label groups, but it did not expose a working project-label creation or application endpoint. The requested label groups were created as workspace labels, and this document records the recommended project-level classifications. Project labels should be applied in Linear UI or through a Linear API workflow when project-label write access is available.

No issue-by-issue relabeling was performed.

## Classification Definitions

| Label | Meaning |
| --- | --- |
| Difficulty: Easy | Low complexity, few dependencies, simple execution. |
| Difficulty: Medium | Moderate coordination or setup, but executable without major external blockers. |
| Difficulty: Hard | Multiple dependencies, platform/legal/account risk, or heavier implementation. |
| Difficulty: Extreme | Very high complexity, high dependency load, high uncertainty, or major operating risk. |
| Duration: Short | Likely days to two weeks once started. |
| Duration: Medium | Likely two to six weeks once started. |
| Duration: Long | Likely six or more weeks, sustained execution, or ongoing cadence. |
| Revenue: Immediate | Can plausibly create or unblock revenue in the near term. |
| Revenue: Delayed | Revenue path exists but depends on setup, approvals, launch, inventory, or sales cycle. |
| Revenue: Strategic | Primarily enables organization, risk reduction, decision quality, or long-term leverage. |

## Recommended Project Classification Table

| Project | Difficulty | Duration | Revenue | Rationale | Operating Recommendation |
| --- | --- | --- | --- | --- | --- |
| Master Business Command Center | Difficulty: Medium | Duration: Short | Revenue: Strategic | Mostly organization and decision clarity; dependencies are internal. | Finish early so every other project has visibility, status, and owner clarity. |
| ShopRite to Arzen Commerce Transition | Difficulty: Hard | Duration: Medium | Revenue: Delayed | High account-risk and document-matching dependency; potential revenue only after safe transition. | Treat as a protected gate project. Do not rush Amazon/Walmart changes. |
| Lightweight Arzen Commerce Website | Difficulty: Medium | Duration: Short | Revenue: Delayed | Straightforward build, but depends on domain/email/name decisions and credible copy. | Execute after operating name is chosen; keep it small and supplier-facing. |
| Supplier Acquisition Engine | Difficulty: Hard | Duration: Long | Revenue: Immediate | Direct path to monetization, but depends on outreach volume, verification, documents, and supplier response. | Start with a lightweight CRM and weekly outreach before overbuilding packets and scoring. |
| Marketplace Profitability System | Difficulty: Hard | Duration: Medium | Revenue: Immediate | Can prevent bad buys and identify profitable products, but needs fee/risk data discipline. | Prioritize before any inventory purchase. Use strict no-buy rules. |
| Workplace Management Solutions Repositioning | Difficulty: Medium | Duration: Medium | Revenue: Immediate | Offers can be sold quickly once positioning, packages, and intake are clear. | Prioritize the first sellable offer and GHL capture before broad website polish. |
| Kinetic Moto Isolation and Launch Readiness | Difficulty: Hard | Duration: Long | Revenue: Delayed | Ecommerce launch has catalog, supplier, website, financing, and lead-capture dependencies. | Keep isolated and time-boxed so it does not distract from Arzen Commerce or WMS revenue. |
| Compliance and Entity Cleanup | Difficulty: Medium | Duration: Medium | Revenue: Strategic | Does not directly create revenue, but reduces legal/admin risk and missed-deadline risk. | Run as a guardrail project with deadline visibility and cleanup decisions. |
| Weekly Operator Dashboard | Difficulty: Easy | Duration: Short | Revenue: Strategic | Low implementation complexity; high leverage for weekly execution. | Keep simple and update weekly. Avoid turning the dashboard into another project. |
| The Driver Network MVP | Difficulty: Extreme | Duration: Long | Revenue: Strategic | Product, compliance, integrations, mobile path, and beta validation are complex and uncertain. | Keep separate from this operating system unless it has a funded or explicitly prioritized runway. |
| Kinetic Moto AI Operations & Lead Automation | Difficulty: Hard | Duration: Long | Revenue: Strategic | Useful internal automation thesis, but broad scope overlaps WMS and Kinetic Moto work. | Collapse near-term work into WMS or Kinetic Moto deliverables unless it has a clear owner and ROI gate. |

## Suggested Dashboard Views

### 1. Revenue Now

Filter:
- Revenue: Immediate
- Status is not Complete

Sort:
- Duration: Short first
- Difficulty: Easy to Hard

Use for:
- Weekly monetization focus
- Selecting the next sales or marketplace action

Projects likely to appear:
- Supplier Acquisition Engine
- Marketplace Profitability System
- Workplace Management Solutions Repositioning

### 2. Quick Strategic Wins

Filter:
- Difficulty: Easy or Difficulty: Medium
- Duration: Short
- Revenue: Strategic or Revenue: Delayed

Use for:
- Work that improves execution without dragging the week sideways
- Dashboard, command center, and credibility site setup

Projects likely to appear:
- Weekly Operator Dashboard
- Master Business Command Center
- Lightweight Arzen Commerce Website

### 3. Risk Gates

Filter:
- Difficulty: Hard or Difficulty: Extreme
- Revenue: Strategic or Revenue: Delayed

Use for:
- Amazon, Walmart, legal, banking, compliance, and entity cleanup decisions
- Work that should not be rushed

Projects likely to appear:
- ShopRite to Arzen Commerce Transition
- Compliance and Entity Cleanup
- The Driver Network MVP

### 4. Over-Scope Watchlist

Filter:
- Difficulty: Hard or Difficulty: Extreme
- Duration: Long
- Revenue: Delayed or Revenue: Strategic

Use for:
- Projects that can absorb a lot of time before producing cash
- Monthly pause/continue decisions

Projects likely to appear:
- Kinetic Moto Isolation and Launch Readiness
- The Driver Network MVP
- Kinetic Moto AI Operations & Lead Automation

### 5. Weekly Execution Board

Filter:
- Duration: Short or Revenue: Immediate
- Status is Not Started or In Progress

Group by:
- Revenue
- Difficulty

Use for:
- Choosing the week's top 5 work items
- Preventing the week from being consumed by low-ROI setup work

### 6. Strategic Guardrails

Filter:
- Revenue: Strategic
- Status is not Complete

Use for:
- Compliance, dashboard, entity-role, and account-protection work
- Keeping risk reduction visible without letting it consume all execution time

## Projects Likely Over-Scoped Relative To Expected ROI

### Kinetic Moto Isolation and Launch Readiness

Risk: Long duration, multiple launch dependencies, and delayed revenue. The project can consume attention through catalog work, supplier setup, financing pages, deployment, and lead capture before proving demand.

Recommendation: Keep the project isolated and time-boxed. Define a small launch-readiness checkpoint before expanding the catalog or financing work.

### The Driver Network MVP

Risk: Extreme difficulty, complex compliance posture, uncertain API/integration access, and unclear near-term revenue relative to the current business operating system.

Recommendation: Keep separate from the business operating system unless there is a funded runway, specific beta objective, or hard go/no-go date.

### Kinetic Moto AI Operations & Lead Automation

Risk: Broad internal automation scope overlaps WMS repositioning and Kinetic Moto launch work. It can become a lab instead of a revenue or operating asset.

Recommendation: Break useful pieces into WMS service packages or Kinetic Moto lead-capture tasks. Pause broad automation research unless tied to a concrete operating outcome.

### Supplier Acquisition Engine

Risk: High ROI potential, but easy to overbuild with packets, scoring, storage, and CRM structure before enough supplier outreach has happened.

Recommendation: Start with 25 to 50 target suppliers, a basic CRM status model, and weekly outreach. Build deeper packet/scoring automation only after the first supplier responses expose real workflow needs.

### Compliance and Entity Cleanup

Risk: Necessary but not revenue-generating. It can expand into legal/admin cleanup that delays sales work.

Recommendation: Limit the first pass to status, due dates, delinquent flags, platform/account connections, and explicit keep/ignore/clean up/reinstate decisions.

## Highest-Leverage Starting Order

1. Master Business Command Center
2. Weekly Operator Dashboard
3. Compliance and Entity Cleanup
4. ShopRite to Arzen Commerce Transition
5. Marketplace Profitability System
6. Supplier Acquisition Engine
7. Workplace Management Solutions Repositioning
8. Lightweight Arzen Commerce Website
9. Kinetic Moto Isolation and Launch Readiness

This order keeps the operating system clear, protects high-risk accounts, and moves quickly toward revenue without letting longer strategic projects take over the week.
