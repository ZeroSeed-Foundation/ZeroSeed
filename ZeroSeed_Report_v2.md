# Zero Seed

## A Constellation for Real-World Coordination

### Structural Plan (Draft) — Version 2  
*Document date: February 2025. This version adds a filled-in structural plan, platform alignment, and a scaffold for product, infrastructure, policy, and governance. The original working report is preserved as sections 1–10; new material is in the Structural Plan (Part B) and the revised Open Questions (§9).*

---

## What is Zero Seed?

Zero Seed is a **coordination substrate** — a "GitHub for real-world work" — stewarded as a nonprofit and designed so local actors can expand practical optionality in uncertain futures. It is not a startup, an ideology, or a replacement for institutions; it is infrastructure for **initiatives**, **discussion**, **attribution**, and **discovery**, built in public and usable without technical expertise.

---

------------------------------------------------------------------------

# Part A: Vision & Context

------------------------------------------------------------------------

# 1. Executive Summary

Zero Seed is a decentralized, nonprofit-stewarded constellation designed to help real-world initiatives move from idea to reality through structured coordination, visible progress, and shared learning.

It exists in response to a world of increasing systemic volatility, cascading risk, institutional inadequacy, and planetary interdependence.

Zero Seed is not:

-   A startup.
-   A political ideology.
-   A replacement for existing institutions.
-   A crypto-native organization.

Zero Seed is:

> A coordination substrate --- a "GitHub for real-world work" --- enabling local actors to expand practical optionality in uncertain futures.

It operates across three interconnected scales:

-   **Local** (where action happens)
-   **Regional** (where density and coherence emerge)
-   **Global** (where interoperability and shared protocol reside)

The goal is not control.\
The goal is tending.

------------------------------------------------------------------------

# 2. Why Zero Seed Exists

We are living in a moment defined by systemic degenerative volatility --- ecological instability, cascading risks, economic fragility, and institutional inadequacy.

The most destabilizing force is not any single endpoint, but the volatility between now and those endpoints.

We have layered information systems, compute systems, monetary systems, and ecological sensing across the globe. The question is no longer whether we are powerful.

The question is whether we can coordinate.

The bottleneck is not innovation.\
The bottleneck is organizing many actors into complexity.

Zero Seed exists to address this coordination bottleneck.

------------------------------------------------------------------------

# 3. Foundational Premises

## 3.1 Interdependence Is Structural

Local realities are entangled with planetary systems. Fortress strategies are illusory.

## 3.2 Optionality Is the Objective

Resilience emerges from preserving and expanding optionality.

## 3.3 Learning Must Replace Control

Organizing must prioritize adaptive learning over rigid instruction.

## 3.4 Culture Precedes Financialization

Sustainable ecosystems grow from norms, care, and contribution --- not speculation.

## 3.5 Infrastructure Must Be Neutral

Zero Seed does not prescribe ideology. It provides coordination infrastructure.

------------------------------------------------------------------------

# 4. Constellation Architecture: Global, Regional, Local

Zero Seed operates as a layered constellation across three interconnected scales:

-   Global
-   Regional
-   Local

These are coordination densities --- not command hierarchies.

## 4.1 Local Layer (Ground Reality)

Local nodes:

-   Surface issues
-   Host initiatives
-   Log deltas
-   Convene gatherings
-   Generate artifacts

All progress begins locally.

## 4.2 Regional Layer (Density & Coherence)

Regional clusters:

-   Enable knowledge exchange
-   Coordinate cross-node initiatives
-   Define shared regional frameworks

## 4.3 Global Layer (Thin Protocol)

The global layer provides:

-   Shared initiative schema
-   Shared delta definition
-   Interoperability standards
-   Global discovery
-   Protocol stewardship

Coherence, not control.

------------------------------------------------------------------------

# 5. Core Components

## Nodes

Locally stewarded hubs operating within a shared protocol.

## Initiatives

Structured efforts addressing real-world issues. Each initiative has a title, description, optional guiding principle, and topics. People can **join** (participate as a member), **support** (star-like signal), and take part in **teams** and **discussions** within the initiative.

## Deltas

Measurable steps that make initiatives more real. (Not yet implemented in the platform; part of the roadmap.)

## Artifacts

Documentation and learning captured from action. In the target product, these are **versioned living documents** with propose → review → merge and discussion tied to sections.

## Playbooks

Replicable models emerging from successful initiatives.

### 5.6 The Platform Today

A first instantiation of this constellation exists as a **web application** (zeroseed). It already provides:

- **Initiatives** — Public list and detail; topic filters; sort by recent activity, support count, or member count; search.
- **Participation** — Join an initiative; support an initiative (star-like); join teams within an initiative.
- **Discussion** — Threaded comments on initiatives; attribution to members; visible activity.
- **Members** — Profiles with initiatives joined, teams joined, comment activity, and a simple network (others who comment on the same initiatives).
- **Discovery** — Browse, search, and see platform-wide stats and activity over time.

Vocabulary is aligned across this report and the platform: **initiative** (top-level effort), **support** (lightweight public endorsement), **join** (membership), **member** (identity with attribution), **node** (future: locally stewarded hub). The app does not yet implement nodes, deltas as first-class objects, versioned documents, or propose-merge workflows; those are in the product roadmap below.

------------------------------------------------------------------------

# 6. Organizational Philosophy: Garden Over Machine

Machine logic: - Optimize - Control - Standardize

Garden logic: - Cultivate - Protect diversity - Tend continuously

Zero Seed is designed for longevity, contribution, and resilience.

------------------------------------------------------------------------

# 7. Relationship to Ethereum

Ethereum may serve as:

-   Settlement rail
-   Treasury infrastructure
-   Transparent funding mechanism

Zero Seed remains a human coordination layer. Culture precedes programmable capital.

------------------------------------------------------------------------

# 8. Operational Ambition

Within 9--12 months:

-   10--25 active nodes
-   Shared delta protocol operational
-   Cross-node replication occurring
-   Distributed stewardship functioning

A Minimum Viable Constellation.

------------------------------------------------------------------------

# 9. Open Questions (Scaffold)

We do not have all the answers. The following are organized as a **scaffold** so we can grow product, infrastructure, policy, and governance together. Each area lists what we are aiming for and what we do not yet know.

## 9.1 Product

- **Current:** Initiatives, join/support, teams, threaded discussions, member profiles, discovery (browse/search/sort), activity and stats. Identity today is "Act as" (simulated member); Google Sign-In is in progress.
- **Next:** Authentication and real identity; versioned **documents** per initiative; **propose → review → merge** (suggest edits to documents, maintainer accepts or declines); **deltas** as first-class objects (measurable steps); discussion threads tied to documents or sections.
- **Later:** Roles and permissions (owner, editor/reviewer, moderator, contributor, viewer); full audit trail and version history; initiative-level principles and optional "how this initiative is organized" diagram; export (Markdown, HTML, PDF); multilingual content.
- **We don’t know yet:** Exact UX for propose-merge for non-technical users; how playbooks are represented (templates? linked initiatives?); how deltas are defined and who can log them.

## 9.2 Infrastructure

- **Current:** Single-tenant web app; SQLite for development (PostgreSQL-ready); REST API; frontend (React, Vite) and backend (Express, Prisma).
- **Next:** Production deployment; PostgreSQL; authentication and session handling; optional self-hosted or multi-tenant options.
- **Later:** **Nodes** as first-class entities (locally stewarded instances or hubs); shared initiative and delta schema across nodes; interoperability and cross-node discovery; APIs and export so data is not locked in.
- **We don’t know yet:** Node topology (federated? instances?); data residency and replication; how regional layers connect technically; hosting and funding model for nodes.

## 9.3 Policy

- **Current:** Public-by-default initiatives and discussions; no formal code of conduct or moderation policy in the product yet.
- **Next:** Clear **code of conduct** and **moderation policy**; transparency about what is visible and to whom; privacy policy and data handling.
- **Later:** Initiative-level moderation (pin, lock, remove posts); optional pseudonyms; retention and deletion policies; handling of harmful content and disputes.
- **We don’t know yet:** Exact moderation escalation path; balance of global vs initiative-level policy; how conflict resolution ties to governance.

## 9.4 Governance

- **Current:** Stewardship and decision-making are outside the scope of the current app; no in-product governance.
- **Next:** Document **who decides what** (stewardship of the constellation, protocol evolution, product roadmap); lightweight conflict resolution for initiative-level disputes.
- **Later:** Distributed stewardship (e.g. across nodes); evolution of roles and permissions; formal process for protocol and schema changes; relationship to legal structure and funding.
- **We don’t know yet:** Incentive structures; node health metrics; legal structure (nonprofit, DAO, hybrid); funding architecture; how governance evolves as the constellation grows.

------------------------------------------------------------------------

# 10. Closing Reflection

We face a fork between mutually assured destruction and mutually assured thriving.

The question is not whether we can innovate.

The question is whether we can organize.

Zero Seed is an experiment in unbounded organizing.

The garden has been seeded.

Now it must be tended.

------------------------------------------------------------------------

# Part B: Structural Plan (Filled-In)

------------------------------------------------------------------------

## How It Works (Three Layers)

| Layer   | What happens here | Platform today | Roadmap |
|--------|--------------------|----------------|---------|
| **Local** | Initiatives, teams, discussions, members, support. Action and attribution live here. | Initiatives, join/support, teams, threaded comments, member profiles, discovery. | Documents, propose-merge, deltas; then nodes as local hubs. |
| **Regional** | Knowledge exchange, cross-node initiatives, shared regional frameworks. | Not yet. | Define regional layer (coordination between nodes); shared frameworks. |
| **Global** | Shared schema, delta definition, interoperability, global discovery, protocol stewardship. | Single app and schema; public discovery. | Multi-node / federated topology; shared protocol; export and APIs. |

Coherence across layers, not top-down control.

------------------------------------------------------------------------

## What We’re Building

### Product roadmap

- **Now**
  - Initiatives (list, detail, topic, sort, search).
  - Join initiative; support initiative; join team.
  - Threaded discussions (comments) with attribution.
  - Member profiles (initiatives, teams, activity, network).
  - Discovery: homepage feeds, initiative charts, platform stats, activity sparklines.
  - Theme (light/dark), nav search, mobile layout, accessibility (skip-to-content, keyboard).
  - Identity: "Act as" member (Google Sign-In in progress).

- **Next**
  - Real authentication and identity.
  - **Documents** per initiative (vision, pillars, resources) with versioning.
  - **Proposed changes**: suggest an edit → maintainer reviews → accept or decline → merge into document (full history).
  - **Deltas**: measurable steps that make initiatives more real (schema and UI).
  - Discussion threads optionally tied to a document or section.

- **Later**
  - Roles and permissions (owner, editor/reviewer, moderator, contributor, viewer).
  - Full audit trail (who did what, when); version history with "merged from Contribution #N by [user]."
  - Initiative-level principles and optional "how this initiative is organized" view (entities, pathways, touchpoints).
  - Export (Markdown, HTML, PDF); multilingual content.
  - **Playbooks**: replicable models (e.g. templates or linked initiatives).

- **Constellation**
  - **Nodes** as locally stewarded hubs within a shared protocol.
  - Cross-node replication and discovery; shared initiative and delta schema.
  - Regional layer: coordination and frameworks across nodes.
  - Global layer: thin protocol, interoperability, stewardship.

### Infrastructure roadmap

- **Now:** Single app; SQLite (dev) / PostgreSQL-ready; REST API; React + Express.
- **Next:** Production hosting; PostgreSQL; auth and sessions; backups and basic ops.
- **Later:** Node topology (federated or multi-instance); data residency; replication; open APIs and export to avoid lock-in.

### Policy roadmap

- **Now:** Public by default; no formal CoC or moderation in-product.
- **Next:** Code of conduct; moderation policy; privacy policy and data handling; transparency (what’s visible, what’s logged).
- **Later:** In-product moderation (pin, lock, remove); initiative-level policies; retention and deletion; conflict escalation.

### Governance roadmap

- **Now:** Stewardship and decisions documented outside the app.
- **Next:** Clear statement of who decides what (constellation, protocol, product); lightweight conflict resolution for initiatives.
- **Later:** Distributed stewardship; node health and incentives; protocol evolution process; legal structure and funding.

------------------------------------------------------------------------

## How to Get Involved

- **Use the platform:** Browse initiatives, join or support, take part in discussions, and explore member profiles.
- **Contribute to the product:** The application and spec are developed in the open; contributions to design, code, and documentation are welcome.
- **Shape the plan:** This document is a scaffold. Feedback and proposals on product, infrastructure, policy, and governance help grow the constellation in line with the goal: coordination and optionality, not control.

------------------------------------------------------------------------

*End of Zero Seed Report v2 — Structural Plan (Draft).*
