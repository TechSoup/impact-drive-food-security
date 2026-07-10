---
type: job-to-be-done
title: Find convenient, dignified food support
personas: [reba, marguerita]
category: [economic-physical-access, utilization-safety, stability-resilience]
validation: validated
maturity: greenfield
market: US food-insecure households near food banks & pantries
---

## Job statement
> When my family needs food and my time, transportation, and money are tight, I want to find a nearby
> pantry that's open when it's convenient and stocks food we'll actually eat, without giving up my
> privacy, so I can feed my family reliably and with dignity.

## The job in two languages
- **Nonprofit framing:** Clients can't easily tell which pantry is open when, where it is, or what it
  stocks, and many won't engage if it costs them their anonymity, especially clients worried about
  safety (e.g. ICE). They end up traveling to the wrong place at the wrong time for food they may not use.
- **Developer translation:** A client-facing discovery + preferences app: searchable/mappable pantry
  directory (hours, location, offerings, delivery/payment), an optional anonymous profile capturing food
  preferences, and a lightweight anonymous feedback loop on what was received and eaten.

## Process / Flow
*Desired-state flow (from the designs):* discover a pantry → check hours/location/selection against my
schedule → choose anonymously → pick up → optionally report what we ate/didn't.
**Current-state flow is a GAP:** how clients find and choose pantries today (calling around, word of
mouth, online searching) needs interviews to document.

## Use cases / user stories
- [Find nearby pantries by hours, location, and selection](../use-cases/find-nearby-pantries.md)
- [Set food preferences and request items in an anonymous profile](../use-cases/client-anonymous-profile.md)
- [Report anonymously what food was eaten and what wasn't](../use-cases/anonymous-food-feedback.md)

## Business case (why it's worth building)
- **Impact / theory of change:** If clients can find the right pantry at the right time for food they'll
  use, we believe access improves, waste drops, and more people engage with support they'd otherwise skip.
- **Market sizing:** see [market-research/sizing-data.md](../market-research/sizing-data.md) *(Iteration 2)*

## Why it's hard
Privacy and dignity are first-order requirements, not features. Anonymity must be real (no PII retained).
See [sector/why-this-is-hard.md](../sector/why-this-is-hard.md) (stigma, access). Clients have limited
data plans and devices, so the experience must be light.
