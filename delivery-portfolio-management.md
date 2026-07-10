# Delivery Portfolio Management

## Purpose

This document covers the portfolio-level view of delivery health across the organisation. It sits above individual engagement management and provides the measures, cadences, and conversations that allow leadership to make proactive decisions about resourcing, hiring, sales alignment, and organisational capability.

The portfolio view is not a reporting layer on top of delivery. It is the mechanism by which delivery informs sales, practice leadership informs hiring, and leading indicators surface before individual engagements feel the pressure.

---

## Objectives

- Maintain a clear, forward-looking view of organisational capacity and demand
- Identify misalignment between the sales pipeline and the delivery workforce before it becomes a resourcing crisis
- Surface cross-engagement risks that are not visible at the individual engagement level
- Support skilling and hiring decisions with data rather than reactive pressure
- Ensure the organisation closes engagements cleanly and captures the knowledge and commercial outcomes that follow
- Surface in-account growth signals from delivery relationships before they are visible to sales

---

## Roles

| Role | Responsibility |
|---|---|
| Delivery Director | Owns the portfolio view; chairs the monthly portfolio review; accountable for cross-engagement health |
| Practice Lead | Owns workforce capability and elasticity data; inputs to hiring and skilling decisions |
| Resource Manager | Owns capacity data; manages allocation across engagements; surfaces utilisation risks |
| Finance Partner | Provides the commercial view of the portfolio; tracks forecast-to-actual variance across engagements |
| Sales Lead | Provides pipeline visibility; co-owns the sales and delivery alignment measures |
| Chief Customer Officer (CCO) | Owns client maturity and long-term account health; delivery-led sales measures are a shared input |
| Delivery Owners | Contribute engagement-level health data; surface cross-portfolio dependencies, risks, and in-account growth signals |

---

## Sales and Delivery Alignment

### Purpose

The sales and delivery alignment measures exist to identify structural misalignment between what the organisation is selling and what it can deliver. Misalignment in either direction is a leading indicator of leakage: revenue leakage when deals are closed that cannot be resourced, and profit leakage when the workforce cannot be aligned to the deals being pursued.

This is a two-way reflection. Both sides of the measure must be read together.

### Measures

**Timing variables**

These measures inform hiring and job assignment decisions. They are reviewed at the monthly portfolio review and used to stress-test the resourcing plan against the deal forecast.

| Metric | Description | Segment | Type | Owner |
|---|---|---|---|---|
| Deal stage for forecast | Pipeline stage distribution, probability-weighted by expected close date | By deal size and complexity | Leading | Sales / Delivery Director |
| Lead time: close to start (p50 / p85) | Elapsed days between contract signature and engagement kickoff, reported as median and 85th percentile rather than a single average | By deal size and complexity | Leading (calibration) | Delivery Director |
| Lead time: advertise to ready (p50 / p85) | Total elapsed days from job posting through to a new hire reaching billable productivity, combining time to hire and onboarding duration into a single end-to-end resourcing lead time, reported as median and 85th percentile rather than a single average | By seniority band | Leading (calibration) | Resource Manager |

> Advertise to ready is the operationally meaningful number for capacity planning. Knowing that a hire takes 30 days to secure and 45 days to reach productivity means the organisation must commit to a hiring decision 75 days before the delivery demand arrives. Tracking the two components separately is useful for diagnosing where delays occur, but the combined figure is what drives the planning decision.
>
> Both lead-time measures are reported as a distribution (p50 / p85), not a mean. This framework treats a delivery plan as a probability distribution, not a commitment, and a mean lead time hides exactly the tail that matters for planning: the p85 is what should drive the hiring decision or the kickoff commitment, because it reflects the case that actually blows out the schedule. A mean of 30 days can sit alongside a p85 of 55 days without the average ever showing it. Where the two figures diverge significantly, that gap is itself a signal worth raising at the pipeline and capacity review.

**Capability variables**

| Metric | Description | Type | Owner |
|---|---|---|---|
| T-shape density as % of population | Proportion of practitioners with a primary deep skill and at least one adjacent skill area, as self-identified or practice manager-identified. Higher density indicates a more elastic workforce. | Leading | Practice Lead |

| What it signals | Implication |
|---|---|
| Rising T-shape density | Increasing elasticity, lower risk of hard resourcing blocks |
| Declining T-shape density | Specialisation is deepening, elasticity is reducing, pipeline diversity risk is rising |
| Density concentrated in a single practice area | Elasticity is not evenly distributed, some deal types remain brittle |

**Alignment variables**

| Metric | Description | Type | Owner |
|---|---|---|---|
| Core skill population as % of total | % of skill base aligned to the primary in-market offer. Higher = stronger alignment of resourcing to sales and marketing effort. | Leading | Practice Lead |
| Deal types with high delivery alignment as % of pipeline | % of sales pipeline aligned to the core skill base. Higher = stronger alignment of sales effort to available resourcing. | Leading | Sales / Practice Lead |

Reading the two metrics together:

| Core skill % | Pipeline alignment % | Signal |
|---|---|---|
| High | High | Strong alignment in both directions |
| High | Low | Workforce is set up for deals the sales team is not closing |
| Low | High | Sales team is closing deals the workforce cannot readily absorb |
| Both declining | — | Structural drift; conversation between sales, delivery, and practice leadership is needed |

**Capacity variables**

| Metric | Description | Type | Owner |
|---|---|---|---|
| Available hours | Total unallocated productive hours across the delivery workforce in the planning window | Point-in-time | Resource Manager |
| Scheduled hours | Total hours committed to active and confirmed engagements in the same window | Point-in-time | Resource Manager |
| Remaining capacity | Available hours minus buffer held for unplanned demand or in-flight engagement overruns | Point-in-time | Resource Manager |

> Remaining capacity is the most operationally sensitive of the three. It should be held above a minimum threshold at all times to absorb natural delivery variance. The threshold is set by the Resource Manager in the context of the current portfolio and hiring position, and reviewed monthly.

### Cadence

| Review | Frequency | Participants | Purpose |
|---|---|---|---|
| Alignment health check | Quarterly | Delivery Director, Practice Lead, Sales Lead | Review trend data on core skill population and pipeline alignment; identify structural drift |
| Pipeline and capacity review | Monthly | Delivery Director, Resource Manager, Sales Lead, Practice Lead | Reconcile weighted pipeline against available and planned capacity; surface hiring or skilling triggers |
| Hiring and skilling review | Monthly (linked to pipeline review) | Practice Lead, Resource Manager, Delivery Director | Confirm hiring lead times against forecast demand; prioritise skilling investment |

---

## Cross-Engagement Measures and Cadences

### Purpose

These measures provide visibility of risks and patterns that exist across the engagement portfolio but are not visible within any single engagement. They allow leadership to identify concentration risks, workforce pressure points, and delivery quality signals before they compound.

### Measures

**Delivery health**

| Metric | Description | Type | Frequency | Owner |
|---|---|---|---|---|
| Client business review completion rate | % of active clients with a completed business review in the current month | Leading | Monthly | Delivery Director |
| Active engagements per Delivery Owner | Number of concurrent engagements held by each Delivery Owner | Leading | Monthly | Delivery Director |
| Engagement health distribution | % of active engagements at Green / Amber / Red | Leading | Fortnightly | Delivery Director |
| Engagements in Recovery and Exception status | Number of active engagements that have met a Recovery and Exception trigger condition and are under Delivery Director review | Leading | Fortnightly | Delivery Director |
| Scope change velocity | Average number of scope changes per engagement per fortnight, reported separately by delivery vehicle: formally agreed changes on fixed-price engagements, and demand expansion on T&M engagements. The two are not the same signal and should not be blended into one portfolio average — rising fixed-price change volume is a scope-control risk, rising T&M demand is a growth signal | Leading | Fortnightly | Delivery Director |
| Unagreed scope drift instances, fixed-price | Number of informal scope additions delivered outside change control on fixed-price engagements, across the portfolio | Leading | Fortnightly | Delivery Director |

**Workforce**

| Metric | Description | Type | Frequency | Owner |
|---|---|---|---|---|
| Skilling gaps identified vs resolved | Number of open skill gaps flagged across active engagements vs number resolved via allocation, hire, or skilling | Leading | Monthly | Practice Lead |
| Billable utilisation (rolling 4-week) | Billable hours as % of available hours across the delivery workforce | Leading | Weekly | Resource Manager |
| Bench time by practitioner | Days without confirmed allocation, by individual | Leading | Weekly | Resource Manager |
| Time to fill open resource gaps | Average days from resource gap identified to confirmed allocation | Leading | Weekly | Resource Manager |

**Commercial**

| Metric | Description | Type | Frequency | Owner |
|---|---|---|---|---|
| Forecast-to-actual revenue variance | Variance between forecast and recognised revenue across the portfolio | Lagging (calibration) | Monthly | Finance Partner |
| Fixed-price engagements with cost-to-complete / EAC variance below target | Number of active fixed-price engagements where remaining budget is forecast to cover less than 100% of the revised cost to complete | Leading | Monthly | Finance Partner / Delivery Director |
| T&M engagements with funding / PO runway below contractual notice period | Number of active T&M engagements where confirmed funded work remaining is shorter than the client's termination notice period | Leading | Fortnightly | Finance Partner / Delivery Director |
| Revenue per head | Total recognised revenue in the period divided by total headcount in the delivery workforce. Tracks volume and rate productivity across the team. | Lagging | Monthly | Finance Partner / Delivery Director |
| Gross margin per head | Gross profit (revenue minus direct delivery cost) divided by total headcount in the delivery workforce. Tracks whether utilisation and rate are translating into profitable output. | Lagging | Monthly | Finance Partner / Delivery Director |

> Revenue and gross margin per head are organisation-level aggregates for portfolio and hiring conversations. They are not individual performance measures, and should not be used to rank or evaluate individual practitioners.

### Cadence

| Review | Frequency | Participants | Purpose |
|---|---|---|---|
| Portfolio health review | Monthly | Delivery Director, all Delivery Owners, Practice Lead, Resource Manager | Review cross-portfolio health distribution, workforce pressure, and concentration risks |
| Workforce review | Monthly | Practice Lead, Resource Manager | Utilisation, bench time, allocation gaps, and skilling investment priorities |
| Finance and forecast review | Monthly | Delivery Director, Finance Partner | Forecast-to-actual variance, revenue recognition status, and commercial risk across the portfolio |

---

## Flow Management

### Purpose

The portfolio already tracks utilisation, bench time, resource-gap fill time, and lead times above. Almost all of that is tracked as a snapshot or an average — a point-in-time reading or a mean, not a managed queue with a limit. The one place a real flow-control policy already exists in this document is Remaining capacity in Sales and Delivery Alignment > Capacity variables, which is held above a minimum threshold at all times specifically to absorb variance. This section extends that same logic — a limit, an aging view, and a pull policy — to the other queues work already moves through across the portfolio: engagements per Delivery Owner, the resource-gap queue, the bench, hiring requisitions, Recovery and Exception status, and the sales-to-delivery handoff. It does not introduce new work; it makes visible, as flow, movement the framework already measures.

### Managed Queues

| Queue | What it is | Limit / aging threshold | Pull policy | Owner |
|---|---|---|---|---|
| Delivery Owner engagement load | Concurrent engagements held by each Delivery Owner, weighted by delivery vehicle complexity rather than counted flat | Complexity-weighted ceiling set per Delivery Owner at the monthly portfolio review | A Delivery Owner at their ceiling does not receive a new engagement without an explicit capacity trade-off decision at the portfolio review: something else moves, is delayed, or another Delivery Owner takes it | Delivery Director |
| Resource gap queue | Concurrently open, unresolved resource gaps the Resource Manager is carrying | Gap open beyond 10 business days | Escalates to the Practice Lead | Resource Manager |
| Bench queue | Practitioners without confirmed allocation, viewed as a queue rather than only as individual bench-time entries | Bench count as a % of total delivery headcount | Read alongside Remaining capacity; if the bench queue grows past what Remaining capacity was sized to absorb, the buffer sizing itself is treated as wrong and revisited, not the bench | Resource Manager |
| Hiring requisition queue | Concurrent open requisitions per practice area | WIP limit on concurrent open requisitions per practice area; aging flag when a requisition exceeds the calibrated advertise-to-ready benchmark for its seniority band | Requisitions exceeding the practice area limit are not posted until an existing requisition closes or the limit is explicitly raised at the hiring and skilling review | Practice Lead |
| Recovery and Exception queue | Engagements currently in Recovery and Exception status | Days an engagement has remained in Recovery and Exception status | An exception open beyond the agreed review interval is escalated as a governance issue in its own right, separate from the underlying engagement problem | Delivery Director |
| Sales-to-delivery handoff queue | Signed-but-not-yet-started engagements queued for Gate 1 / kickoff | Queue length, point-in-time | A growing queue is raised at the pipeline and capacity review as an earlier warning than the lead-time distribution above, before the mean or the p85 shows it | Delivery Director |

**Delivery Owner engagement load.** The existing Active engagements per Delivery Owner metric tracks a count with no ceiling. Engagement weight is not a fixed point-scoring formula: a Phased Program or Structured Project engagement counts for more of a Delivery Owner's ceiling than a Lightweight or Advisory engagement, following the same profile categories set at Gate 1. The ceiling itself is set per Delivery Owner, not fixed globally, because leadership strength and engagement mix vary by person. It is agreed and revisited at the monthly portfolio review.

**Resource gap queue.** Time to fill open resource gaps is currently reported as an average, which hides how many gaps are open at once. The queue-length view — how many unresolved gaps the Resource Manager is carrying at a point in time — surfaces pressure the average cannot. A gap open beyond 10 business days, mirroring the existing bench-time threshold, escalates to the Practice Lead rather than sitting in the average indefinitely.

**Bench queue.** Bench time by practitioner already carries a >10 business day aging threshold for individuals (see Stage 2: Workforce management). This adds a queue-level view — bench count as a % of total delivery headcount — read alongside, not instead of, Remaining capacity. The two measures are connected: Remaining capacity is the buffer sized to absorb variance, and the bench queue is what that buffer is actually absorbing. If the bench queue consistently outgrows what Remaining capacity was sized for, that is a signal the buffer threshold needs resizing, not that individual practitioners are the problem.

**Hiring requisition queue.** Lead time: advertise to ready (p50 / p85) tells the organisation how long a requisition typically takes, and how long the slower tail takes. It does not show how many requisitions are open and competing for sourcing attention at once. A WIP limit on concurrent open requisitions per practice area keeps postings from queuing behind each other indefinitely, and an aging flag on any requisition exceeding the calibrated benchmark for its seniority band gives the Practice Lead an early view of which specific postings are stalling.

**Recovery and Exception queue.** Engagements in Recovery and Exception status is currently a count. An exception that lingers unresolved for months is a governance failure independent of whatever underlying engagement problem triggered it. Tracking days in status surfaces that distinction and prevents a Recovery and Exception entry from becoming a permanent, unexamined feature of the portfolio view.

**Sales-to-delivery handoff queue.** This queue is not currently tracked. Lead time: close to start (p50 / p85) reports how long the transition from signature to kickoff takes on average. The number of engagements currently queued waiting for that transition is an earlier signal: a queue that is growing predicts that the lead-time distribution is about to worsen, before the p50 or p85 shows any movement at all.

### Cadence

Queue and WIP data is reviewed within the existing standing reviews, not a new one. The Delivery Owner engagement load, Recovery and Exception queue, and sales-to-delivery handoff queue are reviewed as part of the monthly Portfolio health review; the resource gap queue and bench queue are reviewed as part of the monthly Workforce review; the hiring requisition queue and both lead-time distributions are reviewed as part of the monthly Pipeline and capacity review. No additional meeting is introduced by this section.

---

## Closure Measures and Cadences

### Purpose

These measures track whether the organisation is closing engagements cleanly and capturing the full commercial and knowledge value of completed work. Poor closure is a portfolio-level risk, not just an individual engagement issue. Patterns in disputed invoices, delayed final billing, or missed retrospectives are signals about organisational process, not individual performance.

Most of these measures are lagging: they confirm whether closure happened cleanly rather than warning that it is at risk. That is an acceptable trade-off at this stage of the framework, since closure is a final compliance check rather than an in-flight signal. The exception is practitioner transition lead time, a leading measure, since it is one place closure risk can still be headed off before it lands.

### Measures

| Metric | Description | Target | Type | Owner |
|---|---|---|---|---|
| Client closure meeting completion rate | % of completed engagements with a documented client closure meeting | 100% | Lagging | Delivery Director |
| Retrospective completion rate | % of completed engagements with a completed internal retrospective | 100% | Lagging | Practice Lead |
| Days from final delivery to final invoice issued | Average elapsed days between confirmed delivery completion and final invoice raised | <5 business days | Lagging | Finance Partner |
| Disputed final invoices | Number of final invoices disputed by clients in the period | 0 | Lagging | Finance Partner |
| Engagements closed via early termination or partial closure | Number of engagements in the period closed via the alternate Gate 2 / Gate 3 route rather than full contracted completion | — | Lagging | Delivery Director |
| Closure Acknowledgement escalations raised to Delivery Director | Number of engagements where the client did not provide a Closure Acknowledgement within 10 business days of request | 0 | Lagging | Delivery Director |
| Practitioner transition lead time | % of practitioners with a confirmed next allocation at least 10 business days before engagement close | 100% | Leading | Resource Manager |
| Retention release rate | % of held retentions released within the agreed timeframe | 100% | Lagging | Finance Partner |
| Finance Handover Record completion rate | % of closed engagements with a completed Finance Handover Record | 100% | Lagging | Finance Partner |
| Knowledge base entry completion rate | % of closed engagements with a completed Delivery Knowledge Base entry | 100% | Lagging | Practice Lead |

### Cadence

| Review | Frequency | Participants | Purpose |
|---|---|---|---|
| Closure health review | Monthly | Delivery Director, Finance Partner, Practice Lead | Review closure metric trends; identify patterns in late invoicing, disputed amounts, missed retrospectives, or a rising rate of early termination and partial closure |
| Retention schedule review | Monthly | Finance Partner, Delivery Director | Confirm upcoming retention release dates and confirm follow-up ownership |

---

## Financial View

### Purpose

The financial view connects delivery health to commercial outcomes. Utilisation and capacity data already gives the organisation a labour cost view. What is missing at the portfolio level is the link between engagement health and the bill-to-cash cycle. A Red commercial health score in Stage 2 is not just a delivery signal. It is a predictor of invoice friction, delayed sign-off, retention holds, and extended collection timelines. This section surfaces that link explicitly so that revenue risk can be seen before it lands in the accounts.

The financial view is co-owned by the Delivery Director and Finance Partner, and reviewed together monthly.

### Measures

**Bill-to-cash pipeline**

The bill-to-cash pipeline view tracks the financial position of every active and recently closed engagement across the four framework stages. It is a point-in-time snapshot reviewed at the monthly finance and forecast review.

| Metric | Description | Type | Frequency | Owner |
|---|---|---|---|---|
| Total contract value in delivery (Stage 2) | Sum of contracted value across all active Stage 2 engagements | Point-in-time | Monthly | Finance Partner |
| Milestone billings due in next 30 days | Value of billing milestones falling due within the next 30 days across the portfolio | Point-in-time | Monthly | Finance Partner |
| Invoices raised but unpaid beyond payment terms | Total value of issued invoices where payment terms have elapsed without receipt | Point-in-time | Monthly | Finance Partner |
| Retentions held across the portfolio | Total value of client-held retentions and their scheduled release dates | Point-in-time | Monthly | Finance Partner |
| Days sales outstanding (DSO) / Mean debtor days | Average number of days between invoice issued and payment received, across the portfolio | Lagging | Monthly | Finance Partner |

**Engagement health to billing friction correlation**

These measures track whether Amber and Red commercial health scores in Stage 2 are predictive of billing friction at Stage 3 and Stage 4. The relationship is directional: poor engagement health is a leading indicator of financial risk, not a coincident one. Tracking the correlation over time allows the organisation to calibrate how seriously to treat commercial health ratings in the weekly and fortnightly reviews.

| Metric | Description | Type | Frequency | Owner |
|---|---|---|---|---|
| % of disputed invoices preceded by Amber or Red commercial health | Of all final invoices disputed in the period, the proportion where the engagement carried an Amber or Red commercial health rating at any point in Stage 2 | Leading (calibration) | Quarterly | Finance Partner / Delivery Director |
| % of extended DSO engagements preceded by Amber or Red commercial health | Of all engagements where DSO exceeded the portfolio average, the proportion with a prior Amber or Red commercial health rating | Leading (calibration) | Quarterly | Finance Partner / Delivery Director |
| Average days from Red commercial health flag to billing milestone resolution | How long, on average, it takes to resolve a billing milestone that was flagged as at risk via a Red commercial health score | Leading | Monthly | Delivery Director |

**Revenue at risk**

Revenue at risk is a probability-weighted view of commercial exposure in the active portfolio. It does not replace the financial forecast. It supplements it with a delivery-informed view of where forecast revenue is most likely to be delayed, reduced, or lost.

| Metric | Description | Type | Frequency | Owner |
|---|---|---|---|---|
| Revenue at risk: Amber engagements | Sum of remaining contract value across engagements currently rated Amber overall, weighted by a probability adjustment agreed between the Delivery Director and Finance Partner | Leading | Monthly | Delivery Director / Finance Partner |
| Revenue at risk: Red engagements | Sum of remaining contract value across engagements currently rated Red overall, with a higher probability adjustment reflecting active commercial risk | Leading | Monthly | Delivery Director / Finance Partner |
| Revenue at risk as % of total active portfolio value | Combined Amber and Red revenue at risk as a proportion of total contracted value in Stage 2 | Leading | Monthly | Finance Partner |

> The probability adjustments applied to Amber and Red engagements are not fixed. They should be calibrated quarterly against the historical correlation data above. An organisation that consistently over-rates or under-rates commercial health will have adjustments that do not reflect reality. Calibration keeps the measure honest.

### Cadence

| Review | Frequency | Participants | Purpose |
|---|---|---|---|
| Finance and forecast review | Monthly | Delivery Director, Finance Partner | Bill-to-cash pipeline position, revenue at risk, DSO trend, and upcoming milestone billings |
| Health-to-billing calibration | Quarterly | Delivery Director, Finance Partner | Review correlation between commercial health ratings and billing friction outcomes; recalibrate probability adjustments for revenue at risk |

---

## Delivery-Led Sales

### Purpose

Delivery teams are in the room when the next opportunity is born. These measures create the habit of capturing that signal systematically. They are not sales metrics. They are delivery-sourced leading indicators of in-account growth potential, reviewed by the Delivery Director and shared with the Sales Lead and CCO as inputs to account planning.

Client maturity metrics are noted here for completeness but are more effectively owned by the CCO, who holds the broader account relationship view.

### Measures

**Relationship depth, scope evolution, and expansion readiness**

Delivery relationships confined to a single layer of the client organisation are a risk signal, not just a growth signal. Client-initiated scope additions and deferred requests are explicit expressions of demand the organisation is not currently capturing. Both signals should flow directly into account planning conversations.

| Metric | Description | Type | Frequency | Owner |
|---|---|---|---|---|
| Out-of-scope requests declined or deferred | Number of requests that fell outside the agreed scope and were either declined or deferred, per engagement per quarter | Leading | Quarterly | Delivery Owner |
| Active relationships by layer | Number of active stakeholder relationships per client, segmented by seniority layer (operational, management, executive) | Leading | Monthly | Delivery Owner |
| Stakeholder relationship sentiment | Delivery Owner-assessed sentiment rating (Positive / Neutral / At risk) for each mapped stakeholder, reviewed at the monthly client business review | Leading | Monthly | Delivery Owner |
| Active follow-on opportunity in CRM as % of active engagements | % of active engagements where a follow-on opportunity has been identified and logged in CRM by the Delivery Owner | Leading | Monthly | Delivery Owner / Sales Lead |
| Rate of client-initiated scope additions | Number of client-initiated scope additions per engagement per fortnight, reported separately for T&M and fixed-price engagements | Leading | Fortnightly | Delivery Owner |

> A high rate of declined or deferred requests that are not flowing into the sales pipeline is a commercial leakage signal. The Delivery Owner is responsible for logging these in CRM and flagging them to the Sales Lead.
>
> Client-initiated scope additions mean different things depending on delivery vehicle, and should not be read as one signal. On a T&M engagement, a rising rate of client-initiated additions that are logged, priced, and resourced is a healthy demand-expansion signal for account planning. On a fixed-price engagement, additions that are agreed and reflected in a revised forecast are the same healthy signal; additions that are absorbed informally without going through change control are not growth, they are unagreed scope drift and a commercial risk — tracked separately as such in the Cross-Engagement measures above and feeding the Recovery and Exception mechanism in Stage 2 if they push the cost-to-complete position past threshold.

**Client maturity** *(CCO-owned)*

Client maturity metrics — including engagement breadth across service types, net revenue per client, and multi-engagement client rate — are more effectively owned and reported by the CCO. The Delivery Director provides delivery-sourced inputs to these measures via the relationship depth and expansion readiness data above.

### Cadence

| Review | Frequency | Participants | Purpose |
|---|---|---|---|
| Delivery-led sales review | Monthly | Delivery Director, Sales Lead, CCO | Review relationship depth, scope evolution signals, and expansion readiness across the active portfolio; align on account planning actions |

---

## Portfolio Metrics Summary

| Metric | Category | Type | Frequency | Owner |
|---|---|---|---|---|
| Out-of-scope requests declined or deferred | Delivery-led sales | Leading | Quarterly | Delivery Owner |
| % of disputed invoices preceded by Amber or Red commercial health | Financial view | Leading (calibration) | Quarterly | Finance Partner / Delivery Director |
| % of extended DSO engagements preceded by Amber or Red commercial health | Financial view | Leading (calibration) | Quarterly | Finance Partner / Delivery Director |
| Deal stage for forecast | Sales and delivery alignment | Leading | Monthly | Sales / Delivery Director |
| Lead time: close to start (p50 / p85) | Sales and delivery alignment | Leading (calibration) | Monthly | Delivery Director |
| Lead time: advertise to ready (p50 / p85) | Sales and delivery alignment | Leading (calibration) | Monthly | Resource Manager |
| T-shape density as % of population | Sales and delivery alignment | Leading | Quarterly | Practice Lead |
| Core skill population as % of total | Sales and delivery alignment | Leading | Quarterly | Practice Lead |
| Deal types with high delivery alignment as % of pipeline | Sales and delivery alignment | Leading | Quarterly | Sales / Practice Lead |
| Available hours | Sales and delivery alignment | Point-in-time | Monthly | Resource Manager |
| Scheduled hours | Sales and delivery alignment | Point-in-time | Monthly | Resource Manager |
| Remaining capacity | Sales and delivery alignment | Point-in-time | Monthly | Resource Manager |
| Active engagements per Delivery Owner | Cross-engagement | Leading | Monthly | Delivery Director |
| Skilling gaps identified vs resolved | Cross-engagement | Leading | Monthly | Practice Lead |
| Client business review completion rate | Cross-engagement | Leading | Monthly | Delivery Director |
| Forecast-to-actual revenue variance | Cross-engagement | Lagging (calibration) | Monthly | Finance Partner |
| Fixed-price engagements with cost-to-complete / EAC variance below target | Cross-engagement | Leading | Monthly | Finance Partner / Delivery Director |
| T&M engagements with funding / PO runway below contractual notice period | Cross-engagement | Leading | Fortnightly | Finance Partner / Delivery Director |
| Revenue per head | Cross-engagement | Lagging | Monthly | Finance Partner / Delivery Director |
| Gross margin per head | Cross-engagement | Lagging | Monthly | Finance Partner / Delivery Director |
| Client closure meeting completion rate | Closure | Lagging | Monthly | Delivery Director |
| Retrospective completion rate | Closure | Lagging | Monthly | Practice Lead |
| Days from final delivery to final invoice issued | Closure | Lagging | Monthly | Finance Partner |
| Disputed final invoices | Closure | Lagging | Monthly | Finance Partner |
| Engagements closed via early termination or partial closure | Closure | Lagging | Monthly | Delivery Director |
| Closure Acknowledgement escalations raised to Delivery Director | Closure | Lagging | Monthly | Delivery Director |
| Practitioner transition lead time | Closure | Leading | Monthly | Resource Manager |
| Retention release rate | Closure | Lagging | Monthly | Finance Partner |
| Finance Handover Record completion rate | Closure | Lagging | Monthly | Finance Partner |
| Knowledge base entry completion rate | Closure | Lagging | Monthly | Practice Lead |
| Total contract value in delivery (Stage 2) | Financial view | Point-in-time | Monthly | Finance Partner |
| Milestone billings due in next 30 days | Financial view | Point-in-time | Monthly | Finance Partner |
| Invoices raised but unpaid beyond payment terms | Financial view | Point-in-time | Monthly | Finance Partner |
| Retentions held across the portfolio | Financial view | Point-in-time | Monthly | Finance Partner |
| Days sales outstanding (DSO) / Mean debtor days | Financial view | Lagging | Monthly | Finance Partner |
| Average days from Red commercial health flag to billing milestone resolution | Financial view | Leading | Monthly | Delivery Director |
| Revenue at risk: Amber engagements | Financial view | Leading | Monthly | Delivery Director / Finance Partner |
| Revenue at risk: Red engagements | Financial view | Leading | Monthly | Delivery Director / Finance Partner |
| Revenue at risk as % of total active portfolio value | Financial view | Leading | Monthly | Finance Partner |
| Active relationships by layer | Delivery-led sales | Leading | Monthly | Delivery Owner |
| Stakeholder relationship sentiment | Delivery-led sales | Leading | Monthly | Delivery Owner |
| Active follow-on opportunity in CRM as % of active engagements | Delivery-led sales | Leading | Monthly | Delivery Owner / Sales Lead |
| Engagement health distribution (% Green / Amber / Red) | Cross-engagement | Leading | Fortnightly | Delivery Director |
| Engagements in Recovery and Exception status | Cross-engagement | Leading | Fortnightly | Delivery Director |
| Scope change velocity (by delivery vehicle) | Cross-engagement | Leading | Fortnightly | Delivery Director |
| Unagreed scope drift instances, fixed-price | Cross-engagement | Leading | Fortnightly | Delivery Director |
| Rate of client-initiated scope additions | Delivery-led sales | Leading | Fortnightly | Delivery Owner |
| Billable utilisation (rolling 4-week) | Cross-engagement | Leading | Weekly | Resource Manager |
| Bench time by practitioner | Cross-engagement | Leading | Weekly | Resource Manager |
| Time to fill open resource gaps | Cross-engagement | Leading | Weekly | Resource Manager |
| Delivery Owner engagement load vs ceiling (WIP limit status) | Flow management | Leading | Monthly | Delivery Director |
| Resource gap queue length (open, unresolved) | Flow management | Leading | Weekly | Resource Manager |
| Resource gaps aged beyond 10 business days | Flow management | Leading | Weekly | Resource Manager |
| Bench queue as % of total delivery headcount | Flow management | Leading | Weekly | Resource Manager |
| Open requisitions vs WIP limit, by practice area | Flow management | Leading | Monthly | Practice Lead |
| Requisitions aged beyond calibrated benchmark, by seniority band | Flow management | Leading | Monthly | Practice Lead |
| Days in Recovery and Exception status | Flow management | Leading | Fortnightly | Delivery Director |
| Sales-to-delivery handoff queue length | Flow management | Leading | Monthly | Delivery Director |
