# WMS Operating System Framework Summary

Created: 2026-05-15

Source files reviewed:
- `Custom Journey Blueprint (public template).xlsx`
- `Customer Journey Blueprint_ Lucidchart.pdf`

Note: the Lucid PDF is a visual board export without an extractable text layer. It was rendered and reviewed visually. The spreadsheet provides the structured source data for stages, workflow naming, tags, plays, and gap scoring.

## Operating Principle

WMS should use this framework as a lightweight operating system for repeatable delivery. The system should define the client journey, the CRM and automation build order, the operational handoffs, and the SOPs needed to deliver consistently across WMS clients, Arzen Commerce, Kinetic Moto, Driver Network, and future implementations.

Do not turn this into a marketing-agency model. The framework is an operational workflow model: lifecycle stages, tags, automations, handoffs, implementation plays, and gap prioritization.

## Core Lifecycle Stages

The framework defines the customer lifecycle as:

| Stage | ID | Operating meaning |
|---|---:|---|
| Target | 10 | Define who should enter the system and what segment, avatar, or account type they belong to. |
| Attract | 20 | Generate awareness and traffic from relevant sources. |
| Capture | 30 | Convert anonymous traffic into a contact, lead, enquiry, or booked action. |
| Engage | 40 | Nurture, qualify, book appointments, and move the contact toward a decision. |
| Offer | 50 | Present proposal, estimate, quote, audit, package, or service offer. |
| Close | 60 | Convert the opportunity into a purchase, signed agreement, payment, or confirmed project. |
| Delivery | 70 | Onboard, fulfill, implement, document, and hand off the work. |
| Impress | 80 | Create a good post-delivery experience, support loop, review, referral, or upsell path. |
| Multiply | 90 | Reactivate, retain, expand, request referrals, and create repeatable growth from existing relationships. |
| Internal | 00 | Internal operations, reporting, tech, finance, and administrative execution. |

## Reusable Operational Patterns

### 1. Build in the Right Order

GoHighLevel and related systems should be built in this sequence:

1. Foundation: settings and infrastructure, custom values, custom fields, tags.
2. Structure: pipelines and opportunity stages, calendars, products and payments.
3. Content and automation: forms and surveys, funnels and websites, email templates, SMS templates, workflows and automations.

Rule: never build automations before the required foundation exists. A workflow built before tags, fields, calendars, or pipeline stages will break or create cleanup work.

### 2. Use a Simple Tag Taxonomy

The spreadsheet defines four reusable tag categories:

| Tag category | Code | Use |
|---|---|---|
| Trigger | T | Starts automations. Usually removed when the automation begins or completes. |
| Status | S | Shows where someone currently is in the journey. Sometimes removed as status changes. |
| Activity | A | Records what someone did. Behavior history; should not be removed. |
| Profile | P | Records who someone is. Segment, avatar, source, role, need, or qualification attributes. |

WMS should preserve this taxonomy across client builds. Each implementation can have client-specific values, but the category logic should stay consistent.

### 3. Name Workflows by Stage

Use numeric stage IDs to keep CRM workflows, SOPs, and Linear work easy to scan:

- `[30.01] New Enquiry - Webform | Chatbot`
- `[40.01] Appointment - Booked`
- `[40.02] Contingency - Emails`
- `[40.03] Value - Sequence`
- `[50.01] Proposal sent`
- `[60.01] Purchase Actions`
- `[70.01] Onboarding`
- `[70.02] Document - Signed`

This keeps systems reusable without forcing a large enterprise architecture.

### 4. Use Plays for Repeatable Delivery

The playbook pattern is:

| Playbook field | Purpose |
|---|---|
| Desired outcome | What should happen for the customer or business. |
| Reporting | What proves the play is working. |
| Stage | Lifecycle stage. |
| Start | What starts the play. |
| Workflow / activity | Emails, SMS, tasks, calls, forms, handoffs, or fulfillment actions. |
| Finish | What completion looks like. |
| Exit | When and why the contact leaves the play. |
| Trigger | Tag, form, pipeline change, calendar event, payment, or manual action. |
| Requirements | Fields, assets, owners, integrations, or approvals required before build. |
| Copy / creative | Templates, scripts, email/SMS copy, forms, landing pages. |
| Other tech | External tools or integrations. |
| Post-launch connections | Reporting, SOPs, downstream workflows, or handoffs. |

### 5. Score Gaps Before Building

The gap scoring framework prioritizes work by:

- Time cost if left unfixed.
- Revenue cost per month.
- Complexity to fix.
- Speed to results.

Decision logic:

- 9 or above: build first.
- 6 to 8: plan and sequence.
- Below 5: defer.

This should be used to prevent overbuilding and keep implementation focused on operational ROI.

## Operational Handoffs

| Handoff | Trigger | Owner | Output |
|---|---|---|---|
| Lead capture to qualification | New enquiry, form, chatbot, call, referral, or inbound message | CRM / sales operator | Contact record, source, profile fields, first status tag, assigned pipeline stage. |
| Qualification to appointment | Appointment booked or qualified lead accepted | Sales / account owner | Calendar event, reminders, qualification notes, appointment status. |
| Appointment to nurture | No-show, not ready, objection, or delayed decision | CRM automation owner | Contingency emails, value sequence, next task, reactivation date. |
| Offer to close | Proposal, estimate, or package sent | Sales / account owner | Offer status, follow-up tasks, proposal assets, close deadline. |
| Close to onboarding | Payment, signed agreement, approved quote, or purchase action | Delivery / operations | Onboarding workflow, intake form, required docs, internal setup task. |
| Onboarding to delivery | Onboarding active and required intake complete | Delivery / implementation | SOP checklist, implementation task list, access list, reporting baseline. |
| Delivery to impress | Work completed, first value delivered, or client milestone hit | Client success / operations | Review request, support path, upsell/referral prompt, satisfaction check. |
| Impress to multiply | Positive outcome, renewal window, inactive segment, or referral opportunity | Retention / growth operator | Reactivation workflow, repeat offer, referral ask, review/case-study action. |

## CRM Stages

The CRM should mirror the lifecycle, but keep opportunity stages practical:

1. New Lead / Enquiry
2. Needs Review
3. Appointment Booked
4. Nurture / Contingency
5. Proposal Sent
6. Follow-Up Active
7. Won / Purchase Complete
8. Onboarding Active
9. Delivery Active
10. Completed / Impress
11. Retention / Reactivation
12. Lost / Not Fit

Pipeline stages should be simple enough for daily operators to maintain. Lifecycle tags can carry more detail than pipeline stages.

## Automation Opportunities

Build automations only where there is a clear repeatable trigger and a clear exit condition.

Recommended first automations:

| Automation | Stage | Trigger | Exit |
|---|---|---|---|
| New enquiry intake | Capture | Form, chatbot, inbound message, referral, or manual contact creation | Contact assigned and first status set. |
| Appointment booked reminders | Engage | Calendar booking | Appointment completed, canceled, or no-showed. |
| Contingency emails | Engage | Not ready, no-show, unresponsive, objection, or delayed decision | Reply, booked appointment, proposal sent, or disqualification. |
| Value sequence | Engage | Qualified but not ready or needs education | Proposal sent, purchase action, or reactivation path. |
| Proposal follow-up | Offer | Proposal or estimate sent | Won, lost, deferred, or reactivation date set. |
| Purchase actions | Close | Payment, signed agreement, or approved quote | Onboarding started. |
| Onboarding start | Delivery | Closed-won or manual trigger | Onboarding complete. |
| Document signed | Delivery | Agreement, intake, or required doc signed | Implementation/delivery checklist created. |
| Review and referral request | Impress | Delivery milestone or completion | Review/referral captured or marked complete. |
| Reactivation | Multiply | Dormant contact, lost-but-qualified lead, renewal date, or inactive client | Re-engaged, not fit, or deferred. |

## Onboarding Stages

Use a lean onboarding sequence that can be copied per client:

1. Closed-won or purchase action confirms the client is ready.
2. Onboarding trigger starts the checklist.
3. Intake form collects required business, access, and workflow details.
4. Documents and agreements are signed.
5. Required access is requested and verified.
6. Baseline reporting is captured.
7. Implementation tasks are created in Linear.
8. Client-facing kickoff or confirmation is sent.
9. Delivery starts.
10. Onboarding is marked complete and activity tag is retained.

## Retention and Reactivation Stages

Retention and reactivation belong in Impress and Multiply, not as separate complex systems.

Recommended stages:

1. Delivery completed.
2. Satisfaction check.
3. Support or issue loop if needed.
4. Review, referral, or testimonial request.
5. Upsell or next service fit.
6. Renewal or repeat engagement date.
7. Dormant or lost-but-qualified reactivation.
8. Periodic value reminder or check-in.
9. Reactivated, deferred, not fit, or closed-lost outcome.

## Mapping to GoHighLevel

| Framework element | GoHighLevel object |
|---|---|
| Lifecycle stages | Pipeline stages plus lifecycle/status tags. |
| Trigger tags | Workflow enrollment triggers. |
| Status tags | Current state markers and segmentation. |
| Activity tags | Permanent behavior and event history. |
| Profile tags | Segments, avatars, sources, needs, account type, qualification. |
| Plays | Workflows with clear start, activity, finish, and exit logic. |
| Avatar map | Custom fields, contact profile fields, and segmentation. |
| Traffic sources | Source fields, tags, attribution fields, and reporting filters. |
| Gap scoring | Build prioritization before CRM configuration. |
| Playbook rows | Workflow requirements and QA checklist before launch. |
| Onboarding | Post-sale pipeline, intake forms, task creation, and internal notifications. |
| Retention/reactivation | Smart lists, workflows, tasks, and review/referral campaigns. |

Minimum GoHighLevel build:

1. Custom values.
2. Custom fields.
3. Tag taxonomy.
4. One lifecycle pipeline.
5. Calendar where needed.
6. Capture forms.
7. Email/SMS templates.
8. Core workflows.
9. Reporting dashboard or source/status views.

## Mapping to Linear

Linear should manage implementation work, not replace the CRM.

| Framework element | Linear object |
|---|---|
| Client implementation | Project or project milestone. |
| Lifecycle stage build | Milestone or grouped issue set. |
| Workflow build | Issue with acceptance criteria and launch checklist. |
| Handoff | Issue checklist or SOP task. |
| Gap score | Issue priority and sequencing note. |
| SOP need | Document or issue linked to implementation. |
| Post-launch fixes | Issues tagged by stage or system area. |
| Cross-client reusable pattern | WMS operating-system document or template issue. |

Recommended Linear structure:

- One WMS operating framework document.
- One lightweight implementation project per client or major internal brand.
- Milestones only where they help sequencing: Foundation, Structure, Core Automations, Delivery SOPs, Retention.
- Issues should be written as operational deliverables, not generic strategy tasks.

Example issue pattern:

```md
Title: [40.02] Build contingency email workflow

Outcome:
Qualified lead receives useful follow-up when not ready, no-showed, or delayed.

Trigger:
Status moves to Nurture / Contingency or tag `[40.02] T / Contingency.Emails.Start` is applied.

Requirements:
- Required custom fields exist.
- Tags exist.
- Email templates approved.
- Exit stages defined.

Acceptance criteria:
- Workflow enrolls only from approved triggers.
- Workflow exits on booked appointment, proposal sent, won, lost, or manual stop.
- Activity/status tags behave according to taxonomy.
- SOP updated with owner and exception handling.
```

## Mapping to SOP Documentation

SOPs should be short, operational, and tied to stages.

Recommended SOP library:

| SOP | Purpose |
|---|---|
| CRM Foundation Setup | Settings, custom values, fields, tags, naming rules. |
| Pipeline and Opportunity Setup | Stages, status changes, owners, handoff points. |
| Lead Capture Intake | Forms, chatbot, contact creation, required fields, source capture. |
| Appointment and Qualification | Booking, reminders, no-show handling, qualification notes. |
| Proposal and Follow-Up | Proposal sent, follow-up cadence, close/lost/deferred outcomes. |
| Closed-Won to Onboarding | Purchase actions, docs, intake, access, delivery handoff. |
| Delivery and Completion | Fulfillment checklist, reporting, client update rhythm. |
| Review, Referral, and Reactivation | Impress/Multiply actions and outcomes. |
| Gap Scoring and Build Priority | How to decide what gets built first. |
| Workflow QA Checklist | Trigger, requirements, copy, tech, finish, exit, reporting. |

Each SOP should include:

- Purpose.
- Trigger.
- Owner.
- Required inputs.
- Steps.
- Exit condition.
- Exception handling.
- Linear issue link or template.
- GoHighLevel objects touched.

## Implementation Recommendations

1. Preserve the source lifecycle and naming framework.
2. Build one reusable WMS operating framework, then copy it into client-specific implementations.
3. Start with foundation, not automations.
4. Use one tag taxonomy across brands.
5. Keep pipeline stages human-readable and use tags for deeper lifecycle details.
6. Create only the automations with real triggers and exits.
7. Use the gap score to prioritize build order.
8. Make Linear the implementation tracker and SOP home, not the runtime workflow engine.
9. Use SOPs as delivery checklists tied to CRM stages and handoffs.
10. Reuse the same core system for WMS clients, Arzen Commerce, Kinetic Moto, Driver Network, and future implementations, with only client-specific fields, assets, and offers changed.

## Recommended First Build Sequence for WMS

1. Define the WMS lifecycle pipeline and opportunity stages.
2. Create the tag taxonomy and naming rules.
3. Define required custom fields and source fields.
4. Create capture forms and source tracking.
5. Build New Enquiry, Appointment Booked, Contingency Emails, Value Sequence, Proposal Sent, Purchase Actions, Onboarding, Document Signed.
6. Create SOPs for each handoff.
7. Create a Linear issue template for each play.
8. Add gap scoring to intake/discovery so future builds stay prioritized.
9. Pilot the system on WMS first.
10. Copy the framework into Arzen Commerce, Kinetic Moto, Driver Network, and future client implementations with only necessary local changes.

