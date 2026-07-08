---
type: job-to-be-done
title: Distribute all donated food each session
personas: [gladys]
category: [availability, utilization-safety, economic-physical-access]
validation: validated
maturity: greenfield
market: US small, volunteer-led, hyper-local pantries (often outside formal networks)
---

## Job statement
> When my church pantry opens for its twice-monthly distribution, I want to give out all the donated food
> we have — matched to what the community actually needs — despite limited storage, few volunteers, and
> little promotion, so nothing is wasted and people are served.

## The job in two languages
- **Nonprofit framing:** A small volunteer-led pantry has limited refrigeration/storage, few volunteers,
  little promotion, and no succession plan. They want to distribute everything donated, to the right
  people, without enterprise tools or much tech skill.
- **Developer translation:** A simple provider dashboard to publish/adjust open hours, post current
  inventory, and receive community requests — usable on an iPad by a non-technical volunteer, with optional
  connection to a broader pantry/food-bank network for visibility and support.

## Process / Flow
*Desired-state flow (from Personal Pantry):* update hours → post current inventory → see what visitors
request → distribute → optionally connect to the regional network for support.
**Current-state flow is a GAP** — how small pantries promote, track inventory, and plan today needs
interviews.

## Use cases / user stories
- [Update pantry hours and inventory from a simple dashboard](../use-cases/provider-update-pantry.md)
- [See and stock items the community requested](../use-cases/community-requested-items.md)
- [Connect a disconnected pantry to the regional network](../use-cases/connect-to-network.md)

## Business case (why it's worth building)
- **Impact / theory of change:** If small pantries can publish hours/inventory and connect to a network,
  we believe more donated food reaches people, waste falls, and isolated pantries gain support and
  resilience (addressing the succession-plan risk).
- **Market sizing:** see [market-research/sizing-data.md](../market-research/sizing-data.md) *(Iteration 2)*
  — note the ~40% of orgs outside Feeding America are the ones that need the most help.

## Why it's hard
The operator is 75, volunteer, time-poor, and uses an iPad + flip phone — so anything built must demand
near-zero tech skill and setup. See [sector/why-this-is-hard.md](../sector/why-this-is-hard.md)
(volunteerism limits, no infrastructure, disconnection from networks).
