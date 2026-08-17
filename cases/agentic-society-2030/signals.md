# Signals

Observable, sourced signals as of August 2026. See [sources.md](sources.md) for full citations.

## Adoption is real but uneven — and mostly not yet autonomous

- Only 13% of enterprises report full-scale agentic AI deployment; 62% remain in
  piloting/experimentation. Gartner projects 40% of agentic AI *projects* will be cancelled by end of
  2027 — the top causes are unclear business value (41%), poor data quality (39%), and escalating
  cost (36%), not capability failure. [First Page Sage]
- Where deployed, the effect is large: 82% of customer-service interactions in adopting firms are now
  handled autonomously; contract review cycles cut by 55%; hiring timelines down 40%. [First Page
  Sage]

## Consumer-facing agentic commerce crossed from pilot to visible infrastructure

- The Universal Commerce Protocol (Google, with Shopify, Etsy, Wayfair, Target) plus the Agent
  Payments Protocol (AP2) now give AI agents a standardized way to discover, purchase, and manage
  post-purchase support — infrastructure, not a single vendor feature. [eMarketer]
- Amazon (Rufus "Auto Buy"), OpenAI (in-chat purchases), Google (AI Mode over 50bn+ listings),
  Perplexity, and Meta all ship agentic shopping capability as of 2026. [eMarketer]
- AI-influenced commerce is no longer trivial: ~$20.6bn in US ecommerce sales in 2026 (1.5% of the
  total, nearly 4x 2025), with McKinsey projecting $3–5 trillion globally by 2030. [eMarketer]
- Behavioural signal: 20% of global Cyber Week 2025 orders involved AI influence; retail AI-chatbot
  traffic up 670% YoY over the same holiday period; 58% of Gen Z/millennial shoppers say they trust
  agents for price comparison and recommendations. [eMarketer]

## Regulation has started treating disclosure, not capability, as the flashpoint

- EU AI Act Article 50(1) took effect 2 August 2026 with no grace period: any system capable of
  interacting with people while scheduling, corresponding, negotiating, or purchasing on their behalf
  must disclose that it is AI and whom it represents — in the interface itself, at first contact, in a
  way that isn't satisfiable by a terms-of-service line or a small "assistant" label. Applies
  regardless of whether the system was built for that purpose, and regardless of open-source
  licensing. [Nerd Level Tech / EU AI Act Art. 50]
- The regulatory reflex, in other words, is not yet "can this agent act" but "does the person on the
  other end know they're dealing with one" — a legitimacy question before it is a safety question.

## Frontier-lab economics are splitting, and agent tooling is going plugin-first

- OpenAI: $14bn non-GAAP operating loss projected for 2026, cumulative losses reaching $44bn by 2028,
  against $665bn in committed data-center capacity — a capex/revenue mismatch, not a rounding error.
  [ValueAddVC — OpenAI]
- Anthropic, by contrast, projects its first quarterly operating profit (~$559m) in Q2 2026 — but that
  margin is explicitly fragile: matching price cuts from Chinese open-weight competitors would erase
  it. This is a **split**, not a uniform "frontier labs are all unprofitable" story — capex-heavy
  scaling bets versus margin-disciplined ones. [ValueAddVC — Anthropic] [VKTR]
- Against that backdrop, DeepSeek released Harness (dsh) as a developer preview on 13 August 2026 — an
  open-source (MIT), plugin-first agent runtime where models, tools, skills, sessions, sandboxes, and
  orchestration are all interchangeable modules, capable of invoking Claude Code or Codex as
  sub-agents. 95,000+ GitHub stars within two days — one of the fastest adoption curves recorded for a
  developer tool. [MarkTechPost] [VentureBeat] [Remio]

## What's not yet a strong signal (flagged, not asserted)

- Large-scale, well-documented cases of agent-caused harm or trust collapse at population scale are
  not yet visible in the sources reviewed for this case — the 2026 evidence base is adoption
  statistics and regulatory response, not incident data. Any scenario built on "trust collapse" should
  be read as a plausible branch, not an observed trend. See [uncertainties.md](uncertainties.md).
- Smaller, specialized, privately-run models displacing general-purpose frontier models is a plausible
  extrapolation from the economics split above, not yet independently evidenced in the sources
  reviewed here. Same for "ad-hoc, disposable tool-building" as a default 2030 pattern — dsh is a
  strong existence-proof of the *architecture* that would enable this, not yet proof that it becomes
  the dominant *behavior*. Needs its own driver/mechanism development, not a scenario claim yet.
