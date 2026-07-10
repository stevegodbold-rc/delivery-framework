# Knowledge Management

## Purpose

Ensure that knowledge created during delivery is captured close to the moment it exists, curated so it stays trustworthy, and consulted at the points in the framework where it would change a decision. Capture without consumption is administration, not knowledge management. This document treats the two as one obligation, not two separate ones.

---

## Position

Knowledge is a portfolio asset. Like workforce capacity or pipeline, it has to be actively managed, not simply generated as a by-product of delivery and left to accumulate. That means capture obligations — someone writes it down — and consumption obligations — someone is required to look at it before repeating a decision it already answers. A knowledge base that is only ever written to is not an asset. It is a filing exercise.

This framework's existing quantitative learning loops and its qualitative records are one knowledge system, not a set of scattered mechanisms that happen to share the word "knowledge." The calibration reviews already in this framework — the Deal Quality at Handover aggregation, the deal-quality-to-downstream-outcome correlation, the estimate-vs-actual solution design variance, the health-to-billing correlation — are knowledge management, expressed as numbers instead of prose. The Delivery Knowledge Base entry, the Account Delivery Record, and the Exception Decision Record are the same activity, expressed as documents instead of numbers. Both are how the organisation learns from what it has already done. Neither is complete on its own.

### The five knowledge streams

The framework currently conflates five distinct kinds of knowledge under a single closure activity. Treating them as one stream is why capture has drifted to a single terminal retrospective: five different kinds of knowledge do not all mature, decay, or get consulted on the same schedule, and a single 45-60 minute meeting cannot serve all five well.

| Stream | What it holds | Where it already lives in the framework |
|---|---|---|
| Client / account knowledge | Stakeholder history, sentiment, what has and has not worked with this client | Account Delivery Record |
| Method knowledge | What went well or badly in how the engagement was run, independent of client or technology | Delivery Knowledge Base entry, retrospective |
| Estimation knowledge | How actual cost and effort compared to what was estimated, and why | Estimate-vs-actual variance reviewed at the Alignment health check |
| Commercial pattern knowledge | How deal quality, pricing, and risk allocation at handover correlate with downstream delivery and billing outcomes | Deal Quality at Handover aggregation, health-to-billing calibration |
| Technical / solution knowledge | Reusable technical assets: accelerators, reference architectures, templates, proven approaches | Not currently held anywhere in the framework |

The fifth stream is new. Technical and solution knowledge is, in a technology professional services business, the single biggest gross-margin lever available to delivery — an accelerator or reference architecture reused on the next engagement is estimation risk removed and delivery cost avoided before the engagement starts, not knowledge applied after the fact. This document introduces a **reusable delivery asset register**: a per-practice-area catalogue of accelerators, reference architectures, and templates, each entry created from work already done and each carrying a simple asset-reuse signal — was this asset consulted or reused on this engagement, logged at the Stage 1 transition meeting and reviewed again at closure.

Framework-methodology neutrality still applies here. This document does not prescribe a knowledge management tool, taxonomy, or vendor. It recommends a storage and representation standard (see OKF, below) and offers schema options as guidance, not requirement.

---

## Roles

| Role | Responsibility |
|---|---|
| Practice Lead | Owns the health of the knowledge system across all five streams; confirms curation happens; owns the reusable asset register per practice area |
| Delivery Owner | Captures knowledge notes at event-driven trigger points; consults prior knowledge at Stage 1 and during solution design; files the closure retrospective and Delivery Knowledge Base entry |
| Delivery Director | Ensures precedent exceptions are tabled at Exception Reviews; reviews staleness and reuse metrics at existing standing forums |
| Resource Manager | Surfaces bench capacity as a pull source for curation work (see Ownership and Cadence, below) |

---

## Capture Across the Framework

The closure retrospective remains the anchor capture point, but it is not the only one, and on longer engagements it is not even the most reliable one. The practitioners who hold the hardest-won lessons on a multi-month engagement frequently rotate off months before the retrospective happens. Waiting for closure to capture their knowledge means it is usually gone by the time anyone asks for it.

This framework already has natural mid-flight events that surface exactly this kind of knowledge, and none of them currently trigger capture:

- **Practitioner rotation.** Someone leaving the engagement before it closes is a capture point in its own right — what they know about the client, the technical approach, or the team does not wait for Gate 2 to matter.
- **Phase go/no-go boundaries** on a phased program. Each phase boundary is already a decision point in Stage 2's methodology interface guidance; it is also a natural point to capture what that phase taught before attention moves to the next one.
- **Re-profiling triggers.** Stage 1's re-profiling triggers (sponsor change, an Exception Review, material scope or duration extension) mark the point where the engagement's own assumptions broke. That is knowledge worth recording at the moment it is discovered, not reconstructed from memory at closure.

**Knowledge note (15 minutes).** At each of these events, the Delivery Owner (or the rotating practitioner, with the Delivery Owner) completes a knowledge note: the same instrument as the closure retrospective, run smaller — what we now know that we did not know before, and what the next person on this engagement, or the next similar engagement, needs to be told. It is not a second retrospective. It is the same exercise, re-run when the evidence says the moment matters, in the same spirit as Stage 1's re-profiling: a lighter, event-triggered version of an instrument the framework already trusts, not a new mechanism.

The closure retrospective (45-60 minutes, Stage 3) remains unchanged in format and continues to produce the Delivery Knowledge Base entry. Where knowledge notes exist from earlier in the engagement, the retrospective consolidates them rather than starting from a blank page — the closure conversation becomes a synthesis of what was already captured, not the first and only capture point.

| Capture point | Instrument | Duration | Owner | Trigger |
|---|---|---|---|---|
| Closure | Retrospective | 45-60 min | Practice Lead / Delivery Owner | Gate 2 |
| Practitioner rotation | Knowledge note | ~15 min | Delivery Owner | Practitioner leaves engagement before closure |
| Phase boundary | Knowledge note | ~15 min | Delivery Owner | Phase go/no-go decision, phased program |
| Re-profiling event | Knowledge note | ~15 min | Delivery Owner | Any Stage 1 re-profiling trigger |

---

## Consumption Across the Framework

Every stage already has a point where consulting prior knowledge would change a decision. None of them currently require it. This section makes consumption an explicit activity at four existing points, rather than adding a new one.

**Stage 1 transition meeting.** The transition meeting agenda gains a prior-knowledge check: relevant Delivery Knowledge Base entries, Account Delivery Record history, and reusable assets for this client, domain, or technology are tabled alongside the existing sales-to-delivery agenda items. This does not lengthen the meeting into a research exercise — it is a query against the knowledge base, not a manual search (see Agent-Driven Curation, below), and its output is a short list of what is relevant, reviewed in the room.

**Solution design on threshold deals.** Where solution design already carries a Practice or Technical Lead co-sign (Stage 1, Solution Design Accountability on Threshold Deals), that co-sign now includes consulting estimate-vs-actual calibration history for comparable engagements. An estimate built without reference to how similar estimates have actually landed is a weaker estimate than one built with it.

**Exception Reviews.** An Exception Review (Stage 2, Recovery and Exception Management) tables precedent Exception Decision Records for comparable trigger conditions, where they exist, alongside the current engagement's own facts. This does not predetermine the decision — the Delivery Director still decides on the specifics of the case in front of them — it means the decision is made with the benefit of how similar exceptions were previously resolved, rather than each Exception Review starting cold.

**Win Review.** The quarterly Win Review already samples 2-4 won deals end-to-end against the framework's own record. It now also asks whether the knowledge trail on each reviewed deal was actually *useful* — would a Delivery Owner picking up a similar deal today have been better placed for having consulted it — not only whether the trail exists. A complete but unused Delivery Knowledge Base entry is a different finding from a complete and useful one, and the Win Review is where that distinction currently goes unexamined.

### Metrics shift from supply to demand

The framework's only knowledge metric to date has measured supply: whether an entry was filed. Filing is necessary but not sufficient, and a 100% completion target on its own drives box-ticking, not use. The metrics below shift the emphasis to demand — is the knowledge base actually being read — while keeping completion as a floor rather than the measure of success.

| Metric | Description | Type | Frequency | Owner |
|---|---|---|---|---|
| Knowledge base entries referenced at Stage 1 per new engagement | Number of prior entries tabled and discussed at the transition meeting's prior-knowledge check | Leading | Per engagement | Delivery Owner |
| Reusable asset reuse rate | Number of reusable assets consulted or reused per engagement, against the register | Leading | Per engagement | Delivery Owner |
| % of knowledge base entries past their review-by date | Proportion of entries whose curation review-by date has lapsed without renewal or retirement | Point-in-time (staleness) | Monthly | Practice Lead |
| Precedent exceptions consulted per Exception Review | Number of comparable Exception Decision Records tabled at each Exception Review | Leading | Per Exception Review | Delivery Director |
| Win Review knowledge-trail usefulness | Delivery Director / CCO assessment of whether the knowledge trail on each sampled deal was useful, not just present | Leading (calibration) | Quarterly | Delivery Director / CCO |
| Knowledge note completion rate at mid-engagement events | % of practitioner rotations, phase boundaries, and re-profiling events with a completed knowledge note | Leading | Per engagement | Delivery Owner |
| Retrospective completion rate | % of completed engagements with a completed internal retrospective | Lagging (floor, not target) | Per engagement | Practice Lead |
| Knowledge base entry completion rate | % of closed engagements with a completed Delivery Knowledge Base entry | Lagging (floor, not target) | Per engagement | Practice Lead |

The last two rows are the framework's existing supply-side metrics, carried over from Stage 3 and the portfolio closure measures unchanged in target (100%). They are retained as a floor — an engagement that fails to file anything at all is still a problem worth flagging — but they no longer stand in as the definition of a healthy knowledge system. The demand-side rows above do that.

---

## The Storage and Format Standard: OKF

This section is guidance, not a mandated toolchain. The framework does not prescribe a knowledge management platform any more than it prescribes a project methodology. It recommends a representation standard because the framework's records are already document-shaped — the Delivery Handover Record, the Account Delivery Record, the Exception Decision Record, and the Delivery Knowledge Base entry are all, in practice, structured prose with a few key fields. A format that makes that shape portable, versionable, and machine-readable is a natural fit rather than a new discipline being imposed on the framework.

The recommended standard is the **Open Knowledge Format (OKF) v0.1**, published June 2026 by Google Cloud's Data Analytics team: an open, vendor-neutral specification formalising what has become known as the "LLM wiki" pattern.

- Specification and background: https://cloud.google.com/blog/products/data-analytics/how-the-open-knowledge-format-can-improve-data-sharing/
- Spec repository: https://github.com/GoogleCloudPlatform/knowledge-catalog/tree/main/okf

### What OKF is

- Knowledge is represented as a directory of markdown files with YAML frontmatter, one concept per file.
- The only mandatory frontmatter field is `type`. Standard queryable fields beyond that are `title`, `description`, `resource` (a URL back to the underlying system record — the CRM entry, the Engagement Health Register row, the ticketing system item), `tags`, and `timestamp`.
- Two optional directory conventions: an `index.md` per directory for progressive disclosure and navigation, and a `log.md` for a chronological change history.
- Concepts link to each other with normal markdown links. That is what turns a directory of files into a queryable knowledge graph — no separate graph database or proprietary index is required.

### Why it fits this framework

- **Minimally opinionated.** The spec defines the interoperability surface — how a concept is named, tagged, and linked — not the content model. This framework can define its own `type` taxonomy and frontmatter conventions on top of OKF without needing the spec's permission or a platform migration to change them.
- **Producer/consumer independence.** A human-authored knowledge note, a vendor-exported CRM record, and an LLM-generated draft are all consumable by any conformant OKF reader. The format is the contract; the tooling that reads or writes it is swappable.
- **Format, not platform.** There is no proprietary SDK, licence, or account required. The knowledge base is plain files, git-friendly, diffable, and readable in any text editor — the same properties that make this framework's own documents easy to review and version.
- **Directly consumable by AI agents without a proprietary catalog.** This matters specifically for the consumption points in the previous section: a prior-knowledge check that has to be a manual search does not scale, but a directory of OKF documents is queryable by any agent that can read markdown and YAML.

---

## Schema Options

The framework does not prescribe one schema. Consistent with its methodology-agnostic stance, the options below are guidance: pick one, adapt it, or design a different one that still conforms to the OKF baseline (mandatory `type` field, markdown body, directory-of-files structure).

### A `type` taxonomy for this framework's artifacts

| OKF `type` | Framework artifact | Stream |
|---|---|---|
| `Engagement Retrospective` | Closure retrospective / Delivery Knowledge Base entry | Method |
| `Knowledge Note` | Mid-flight capture at rotation, phase boundary, re-profiling | Method (and whichever stream the note concerns) |
| `Account Delivery Record` | Per-account rollup maintained by the account Delivery Owner | Client / account |
| `Exception Decision Record` | Output of an Exception Review | Method / commercial |
| `Reusable Asset` | Accelerator, reference architecture, or template in the asset register | Technical / solution |
| `Estimate Calibration` | Estimate-vs-actual entry reviewed at the Alignment health check | Estimation |
| `Client Profile` | Stakeholder map and sentiment history for a client, often the `index.md` for an account's directory | Client / account |
| `Practice Playbook` | Practice Lead-curated pattern distilled across multiple engagements | Method |

### Option A: minimal frontmatter, knowledge in prose

Only the mandatory `type` field plus the OKF standard fields (`title`, `description`, `resource`, `tags`, `timestamp`). All framework-specific detail — client, delivery vehicle, confidence, review date — lives in the body as prose under headings mirroring the retrospective agenda.

Trade-off: lowest authoring effort, fastest to adopt, and closest to how the retrospective already runs. But it cannot be queried structurally — "show me every entry tagged Amber commercial health for this client" requires reading the prose, not filtering a field. Best suited to teams adopting the knowledge base for the first time, or practice areas with low entry volume.

### Option B: richer frontmatter, structured queries

Adds framework-specific extension fields to the standard OKF set:

- `engagement_vehicle` — Lightweight / Advisory / Structured Project / Phased Program, matching Stage 1's delivery vehicle categories
- `delivery_stage` — the stage the entry was captured at (useful for distinguishing a mid-flight Knowledge Note from a closure Engagement Retrospective)
- `client` — anonymised or coded reference, never the client's name in plain text (see Considerations, below)
- `practice_area`
- `review_by` — the curation lifecycle date (see Agent-Driven Curation, below)
- `confidence` — the author's own confidence in the entry's continued relevance, Green / Amber / Red, in the same idiom as the engagement health score

Trade-off: higher authoring effort per entry, but enables the structured queries the consumption points in this document actually need — filtering the prior-knowledge check by client, technology, or practice area rather than presenting every entry ever filed. Best suited once a practice area has enough volume that unfiltered browsing stops working.

Nothing prevents mixing: adopt Option B's `review_by` and `confidence` fields immediately (they support curation regardless of volume) while deferring `engagement_vehicle` and `practice_area` until query volume justifies the extra authoring effort.

### Worked example: a Delivery Knowledge Base entry

```markdown
---
type: Engagement Retrospective
title: "CLIENT-0412 — Order Management Replatform, closure retrospective"
description: >
  Retrospective and knowledge base entry for the CLIENT-0412 order
  management replatform, closed 2026-06-30.
resource: "https://crm.internal/engagements/NW-4471"
tags: [logistics, order-management, azure, fixed-price, phased-program]
timestamp: 2026-06-30
engagement_vehicle: "Phased Program"
delivery_stage: "Stage 3 closure"
client: "CLIENT-0412"
practice_area: "Data & Platform"
review_by: 2027-06-30
confidence: Amber
---

# CLIENT-0412 — Order Management Replatform

## What went well that we should repeat

Early phase gate discipline (see [phase 1 knowledge note](./knowledge-note-phase1.md))
caught a sponsor-side data ownership gap before it became a phase 2 blocker.

## What did not go well that we should change

Estimate for the integration layer under-called effort by roughly 30%; see
[estimate calibration entry](../estimation/nw-4471-integration-layer.md) for the
detail behind that number.

## What we learned about the client, the technology, or the delivery approach

Client's legacy order system has an undocumented batch dependency window —
now captured in the [account record](../accounts/CLIENT-0412/index.md) so the
next engagement in this account does not rediscover it.

## Commercial or scope issues to handle differently next time

Scope renegotiation triggered one Exception Review; see
[exception decision record](../exceptions/nw-4471-scope-renegotiation.md).

## Follow-on opportunities

Logged in CRM; a phase 3 reporting layer extension is a plausible next
engagement — flagged to the account Delivery Owner.

## Reusable assets produced

- [Batch-window detection accelerator](../assets/batch-window-detector.md)
- [Order management reference architecture, Azure variant](../assets/reference-architectures/order-mgmt-azure.md)
```

The links above are ordinary markdown links. Nothing distinguishes an OKF knowledge graph from a normal folder of interlinked markdown files, which is the point: the retrospective links to the account record, the exception record, and the reusable assets it produced, and any conformant reader — human or agent — can walk that graph without a database.

---

## Agent-Driven Curation, Indexing, and Management

OKF's explicit design target is an LLM-agent-operated knowledge base, in the "LLM wiki" style: a directory of markdown files an agent can read, draft, and update, precisely because the format is plain enough for both humans and agents to work in without a proprietary tool. This is where the framework's capture and consumption obligations actually become sustainable at scale, rather than depending entirely on already-stretched people remembering to write things down and look things up. Agents do not get bored, do not forget to update a cross-reference, and can touch fifteen files in one pass in the time it takes a person to open the first one.

Four agent roles, defined here as guidance rather than a mandated architecture:

- **Enrichment agent.** Drafts entries from framework artifacts already produced — Engagement Health Register history, Exception Decision Records, closure documents, Account Delivery Record updates — for human review. It does not create knowledge; it drafts a first pass at recording knowledge that already exists in the framework's own records, so a person is editing rather than starting from a blank page.
- **Curation agent.** Handles dedupe, flags entries past their `review_by` date, repairs broken links when files move or are renamed, and maintains `index.md` navigation files. This is the curation lifecycle the framework currently has no mechanism for at all — the same discipline retentions get by being diarised, applied to knowledge instead.
- **Indexing / retrieval agent.** Serves the consumption points defined above. The Stage 1 prior-knowledge check becomes a query this agent runs and presents, not a manual search through a shared drive; the same applies to solution design's estimate history lookup and the Exception Review's precedent lookup.
- **Aggregation support** for the calibration reviews — the Deal Quality at Handover rollup, the estimate-vs-actual variance, the health-to-billing correlation — drawing structured fields (where Option B schema fields are in use) into the existing quarterly Calibration Block rather than requiring manual collation beforehand.

### Human-in-the-loop stance

Agents draft and maintain; people confirm. This is the same logic this framework already applies to workforce decisions: data and dialogue to support good decisions, not a mechanism that predetermines the outcome. An enrichment agent's draft entry is not a filed entry until a person — typically the Delivery Owner or Practice Lead — reviews and confirms it. A curation agent's staleness flag is a prompt for a conversation about whether the entry is still true, not an automatic deletion.

### Considerations

- **Client confidentiality.** Entries reference client work by nature. Client identity should be anonymised or coded (see the `client` field in Schema Option B) rather than named in plain text, and commercially sensitive terms — specific pricing, discount levels, contractual penalty clauses — should never enter the knowledge base at all. Where a lesson genuinely depends on commercial specifics, the entry should describe the pattern, not reproduce the figure.
- **Agent write access and review gates.** Enrichment and curation agents should have write access to draft files, not to the confirmed record. A simple convention — drafts land in a `_drafts/` subdirectory or carry a `status: draft` field until a human confirms them — keeps the distinction visible rather than relying on memory.
- **Hallucination risk in agent-drafted content.** The `resource` field exists specifically to manage this: every agent-drafted entry should carry a working link back to the source record it was drafted from (the CRM entry, the Engagement Health Register row, the Exception Decision Record), so a reviewer can check the draft against its provenance rather than trusting it at face value.
- **Where the knowledge base sits relative to systems of record.** The OKF bundle is the interoperability and knowledge layer. CRM remains the system of record for client and pipeline data; the Engagement Health Register remains the system of record for engagement health history. The knowledge base references those systems (via `resource`) rather than duplicating or replacing them.
- **Adoption sequencing.** Start with one practice area's directory, not a big-bang migration across all five knowledge streams at once. A single practice area running the closure retrospective, one mid-flight knowledge note, and the prior-knowledge check through an OKF directory for one quarter tells the organisation more about what works than a portfolio-wide rollout designed on paper.

---

## Ownership and Cadence

The Practice Lead owns the knowledge system's health across all five streams, consistent with their existing accountability for the Delivery Knowledge Base entry and the retrospective. This document does not add a new standing forum. It adds a protected agenda segment to the monthly **Workforce Review** (Practice Lead, Resource Manager): a standing item covering knowledge system health — staleness flags outstanding, curation backlog, asset register updates, and the demand-side metrics above. This forum already carries the Practice Lead's workforce and skilling accountability and already includes the Resource Manager, which matters for the point below.

Curation is real work and needs a protected slot rather than being squeezed into an already-overloaded Practice Lead's spare time. Flow Management's own logic in the portfolio document already establishes the bench queue as a managed queue with a pull policy; curation work — reviewing enrichment agent drafts, resolving staleness flags, filling gaps in the asset register — is exactly the kind of bounded, valuable work the bench queue is meant to pull toward, rather than bench time going unused while the knowledge backlog grows unaddressed. This is proposed as a pull source, not a mandatory assignment: a practitioner on the bench picking up a curation task is a Resource Manager and Practice Lead decision, made the same way any other bench-queue allocation is made.

The existing Alignment health check, co-scheduled within the quarterly Calibration Block, remains the home for the quantitative learning loops — Deal Quality at Handover aggregation, estimate-vs-actual variance, deal-quality correlation — since those already sit there and are calibration data in the same sense as the qualitative streams. No new meeting is introduced by this document.

| Element | Owner | Review frequency |
|---|---|---|
| Knowledge system health (staleness, curation backlog, asset register) | Practice Lead | Monthly, Workforce Review |
| Quantitative calibration loops (Deal Quality, estimate-vs-actual, health-to-billing) | Delivery Director / Practice Lead / Finance Partner | Quarterly, Calibration Block |
| Bench capacity as a pull source for curation work | Resource Manager + Practice Lead | As bench queue allows, per Flow Management |
| Win Review knowledge-trail usefulness sampling | Delivery Director / CCO | Quarterly, Calibration Block |

---

## Metrics Summary

| Metric | Category | Type | Frequency | Owner |
|---|---|---|---|---|
| Knowledge base entries referenced at Stage 1 per new engagement | Knowledge management | Leading | Per engagement | Delivery Owner |
| Reusable asset reuse rate | Knowledge management | Leading | Per engagement | Delivery Owner |
| % of knowledge base entries past their review-by date | Knowledge management | Point-in-time (staleness) | Monthly | Practice Lead |
| Precedent exceptions consulted per Exception Review | Knowledge management | Leading | Per Exception Review | Delivery Director |
| Win Review knowledge-trail usefulness | Knowledge management | Leading (calibration) | Quarterly | Delivery Director / CCO |
| Knowledge note completion rate at mid-engagement events | Knowledge management | Leading | Per engagement | Delivery Owner |
| Retrospective completion rate (floor) | Knowledge management | Lagging | Per engagement | Practice Lead |
| Knowledge base entry completion rate (floor) | Knowledge management | Lagging | Per engagement | Practice Lead |
