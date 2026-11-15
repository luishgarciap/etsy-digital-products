# Process Map and Traceability

[Home](README.md) · [Process](process-map.md) · [Platform baseline](knowledge/platform-baseline.md) · [Economics baseline](knowledge/economics-baseline.md) · [Iteration 01](discovery/iteration-01/opportunity-frame.md) · [Strategic decisions](decisions/strategic-decision-log.md) · [References](knowledge/references.md)

---

This page defines how the methodology maps to the BoK. Each iteration is a **closed decision case**: it starts with a frame and ends with an explicit iteration outcome.

## End-to-end traceability

| Step | Primary artefact | Inputs | Key activity | Output | Feeds |
|---|---|---|---|---|---|
| **FRAME** | `opportunity-frame.md` | Previous iteration outcome (if any), strategic decisions, shared knowledge | Define what must be decided now | Investigation question + candidate scope | INVESTIGATE |
| **INVESTIGATE** | `market-demand.md` | Opportunity frame | Search demand, supply, buyer-intent evidence | Market evidence | SYNTHESISE |
|  | `competitors.md` | Opportunity frame + market evidence | Shops, offers, reviews, gaps | Competitor/customer evidence | SYNTHESISE |
|  | `product-economics.md` | Opportunity frame + economics baseline + observed prices | Apply fees, price and production assumptions | Candidate economics | SYNTHESISE |
| **SYNTHESISE / REFINE** | `opportunity-assessment.md` | All investigation artefacts + platform baseline | Integrate evidence and narrow/redefine opportunities | Refined candidate set | COMPARE |
| **COMPARE** | `product-comparison.md` | Opportunity assessment | Compare candidates on common decision criteria | Comparison + ranking | DECIDE |
| **DECIDE** | `pilot-decision.md` | Product comparison | Select primary/backup candidates and test scope | Approved pilot decision | PILOT |
| **IMPLEMENT / PILOT** | `pilot-plan.md` | Pilot decision + platform/economic baselines | Create/publish controlled test | Live pilot | MEASURE |
| **MEASURE** | `measurement.md` | Pilot plan + Etsy results | Record observed behaviour and economics | Results | LEARN |
| **LEARN** | `learning-review.md` | Measurement + original hypotheses | Interpret what changed | Learning conclusions | OUTCOME |
| **ITERATE / EXIT** | `iteration-outcome.md` | Learning review | Decide next business action | New iteration frame / operate / pivot / stop | Next cycle or operations |

## Iteration boundary

An iteration is complete only when `iteration-outcome.md` has been written.

If the outcome is **another discovery iteration**, the next `opportunity-frame.md` is a new artefact. It is informed by the previous:

```text
opportunity-assessment
        +
pilot-decision
        +
measurement
        +
learning-review
        +
iteration-outcome
        ↓
NEXT opportunity-frame
```

The next frame is **not a copy** of the previous assessment. It states the new decision question after incorporating what has been learned.

## Shared knowledge vs iteration evidence

```text
knowledge/
    platform-baseline.md
    economics-baseline.md
    references.md
             │
             │ reused by
             ▼
discovery/iteration-01/
             │
             ▼
discovery/iteration-02/
             │
             ▼
future iterations
```

A baseline is kept outside an iteration only when it remains useful regardless of which product is being evaluated.

Examples:

- Etsy listing fee → shared economics baseline.
- Brazil uses Etsy Payments through Payoneer → shared platform baseline.
- Expected margin for a specific matcha-menu product → Iteration 01 product economics.
- Customer complaints about a specific invitation format → Iteration 01 competitor evidence.

## Governance rule

`decisions/strategic-decision-log.md` contains only project-wide decisions. Product-specific decisions remain inside the iteration that produced them.

---

**Iteration 01:** [Start with the opportunity frame →](discovery/iteration-01/opportunity-frame.md)
