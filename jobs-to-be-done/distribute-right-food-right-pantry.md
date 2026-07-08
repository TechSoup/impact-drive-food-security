---
type: job-to-be-done
title: Distribute the right food to the right pantries before it spoils
personas: [dan]
category: [availability, utilization-safety]
validation: validated
maturity: greenfield
market: US food banks moving inventory to networks of pantries
---

## Job statement
> When food is sitting in the warehouse and starting to age, I want to send the right items to the
> pantries that can actually use them — including small ones I can't see today — so I move it out before it
> spoils and it reaches people who want it.

## The job in two languages
- **Nonprofit framing:** A food-bank program manager has to clear warehouse stock before spoilage but
  doesn't know each pantry's current capacity or what its visitors actually need or eat — so the wrong
  food goes to the wrong place and gets wasted. Small, disconnected pantries are invisible to him.
- **Developer translation:** An allocation/visibility tool over (privacy-safe) aggregated pantry data:
  current capacity, inventory, visitor preferences and consumption, plus a regional map that surfaces
  pantries — including newly-joined small ones — to inform what to send where.

## Process / Flow
*Desired-state flow (from the designs):* view aggregated pantry inventory/orders (no PII) → see regional
map incl. new/small pantries → match warehouse stock to capacity + demonstrated need → distribute.
**Current-state flow is a GAP** — how Dan decides allocations today needs interviews. (This is a
classic *missing-data* problem: he's largely operating without the data, with waste as the consequence.)

## Use cases / user stories
- [View aggregated pantry inventory and consumption without PII](../use-cases/aggregated-pantry-data.md)
- [Discover newly-joined and nearby pantries on a regional map](../use-cases/discover-pantries-on-map.md)
- [Match warehouse stock to pantry capacity and demonstrated need](../use-cases/match-stock-to-need.md)

## Business case (why it's worth building)
- **Impact / theory of change:** If Dan can see real capacity and demonstrated need across his region, we
  believe less food spoils, allocation matches demand, and small disconnected pantries get pulled into
  support. The "special sauce" here is the data collection as much as the product.
- **Market sizing:** see [market-research/sizing-data.md](../market-research/sizing-data.md) *(Iteration 2)*

## Why it's hard
This is mostly a **greenfield, missing-data** problem — the data doesn't exist in usable form today, and
gathering it must never expose client PII. See [sector/why-this-is-hard.md](../sector/why-this-is-hard.md)
(data fragmentation, disconnection from networks, trust).
