# Zero Seed: Launch Checklist

A single place to track what’s needed to **launch** and **grow** Zero Seed. Update this doc as things get done or new tasks appear. Think of it as the mission control checklist (minus the rocket fuel).

**Last updated:** February 2025

---

## How to use this doc

- **Sections** are grouped by theme (Website, Onboarding, Product, etc.).
- **Checkboxes** — tick them when done; add new rows as needed.
- **Links** — point to the actual specs (Vision, Report, Production Readiness, repos).
- **Product features** are not fully listed here; they live in **ZeroSeed_Report_v2.md** (Part B: Product roadmap) and in the **zeroseed** app repo. This doc references them and tracks “launch/growth” tasks around the product.

---

## 1. Website (Landing / zeroseed_website)

The public face: vision, principles, platform teaser, and ways to join or get in touch.

| Task | Status | Notes |
|------|--------|--------|
| Get landing page deployed (live URL) | ☐ | e.g. zeroseed.org or similar |
| Point “Explore the Platform” to real app URL | ☐ | Currently `href="#"` |
| Point “Read the Vision” to vision/paper | ☐ | e.g. ZeroPaperDraft.md or a published page |
| Add and verify **contact form** (e.g. email or form backend) | ☐ | So visitors can reach you without hunting for email |
| Footer links: Platform, Vision, GitHub (real URLs) | ☐ | Replace placeholders |
| Optional: Simple analytics (privacy‑respecting) | ☐ | e.g. Plausible, Fathom — only if you want and with consent |
| Optional: Favicon, meta description, Open Graph for sharing | ☐ | Better sharing and SEO |

---

## 2. New Collaborator Onboarding

**Where can someone go to get onboarded quickly?**

| Item | Status | Notes |
|------|--------|--------|
| **Single “start here” link or doc** | ☐ | e.g. this doc + “Read this first” section below |
| **One-pager: What is Zero Seed?** | ☐ | Link to ZeroSeed_Report_v2.md §1–2 or a short summary page |
| **Vision / why we exist** | ☐ | ZeroSeedVisionDraft.md and/or ZeroPaperDraft.md — link from onboarding |
| **Where the code lives** | ☐ | zeroseed (app), zeroseed_website (landing); document in README or this doc |
| **How to run the app locally** | ☐ | Already in `zeroseed/README.md` — link from onboarding |
| **Ways to contribute** | ☐ | Code, design, docs, initiatives, node stewardship — list in one place |
| **Who to contact / where to ask questions** | ☐ | Contact form, email, or Discord/forum link; put in onboarding and footer |

**Suggested “Start here” for new collaborators:**

1. **What is Zero Seed?** → [ZeroSeed_Report_v2.md](./ZeroSeed_Report_v2.md) (Part A, §1–2 and Part B).
2. **Vision & tone** → [ZeroSeedVisionDraft.md](./ZeroSeedVisionDraft.md) (and ZeroPaperDraft.md if you use it).
3. **What we’re building (product roadmap)** → [ZeroSeed_Report_v2.md](./ZeroSeed_Report_v2.md) Part B — “What We’re Building”.
4. **Run the app** → [zeroseed README](https://github.com/your-org/zeroseed) (or local path: `../zeroseed/README.md`).
5. **Get in touch** → [Contact form / email / community link] (fill in when you have it).

*(Update the “Start here” links when you add a dedicated onboarding page or repo.)*

---

## 3. Product Checklist (App — zeroseed)

**Detailed product roadmap and feature list** → **ZeroSeed_Report_v2.md** Part B (“What We’re Building” — Product roadmap).  
**Production readiness (legal, security, i18n, infra)** → **zeroseed/PRODUCTION-READINESS.md**.

This section is a **launch-oriented** checklist around the app, not the full feature list.

| Task | Status | Notes |
|------|--------|--------|
| Production deployment (backend + frontend) | ☐ | Hosting, env, DB (PostgreSQL when you’re ready) |
| Auth in production (Google OAuth + JWT) | ☐ | Callback URLs, secrets, FRONTEND_URL / BACKEND_URL |
| Landing page “Explore the Platform” points to this app | ☐ | So “launch” = website + app both live |
| Privacy policy & terms (or placeholders + “coming soon”) | ☐ | See PRODUCTION-READINESS.md §1 |
| Basic security (HTTPS, CORS, env vars, no secrets in frontend) | ☐ | See PRODUCTION-READINESS.md §3 |
| Error tracking / monitoring (e.g. Sentry) | ☐ | Optional but recommended for production |

**For full feature checklist (documents, deltas, propose-merge, nodes, etc.)** use the **Product roadmap** in ZeroSeed_Report_v2.md and track implementation in your issue tracker or dev doc.

---

## 4. Governance & Operations

Things that help the initiative run and scale without relying on a single bottleneck.

| Task | Status | Notes |
|------|--------|--------|
| Document “who decides what” (product, protocol, stewardship) | ☐ | Report §9.4 Governance roadmap — make it easy to find |
| Code of conduct & moderation policy | ☐ | Report §9.3 Policy roadmap; PRODUCTION-READINESS.md |
| Funding / sustainability (optionality, multiple backers) | ☐ | Per Vision: avoid single-source dependency |
| Where to report bugs or suggest features | ☐ | GitHub issues, contact form, or both — linked from app and website |

---

## 5. Research & Learning

*Mini research project: 7–10 interviews with thinkers/doers across geographies (motivations, ideation, action, tooling gaps); optional prototype feedback in final 5–10 min; target completion end of March. See full Research Plan for participants, questions, and areas to capture.*

| Task | Status | Notes |
|------|--------|--------|
| **Synthesize research and feed into Zero Seed** | ☐ | Map interview findings (motivations, how people ideate/act, tooling gaps, friction) into product roadmap, messaging, and onboarding so the initiative is informed by real practice |
| **Document how research informs the initiative** | ☐ | Decide where findings live, who owns synthesis, and how they flow into roadmap/vision/positioning so the work doesn’t sit in a silo |

---

## 6. Growth & Movement

Beyond “it works” — so more people can find and join.

| Task | Status | Notes |
|------|--------|--------|
| **Soft launch on LinkedIn** (coordinated timing) | ☐ | Agree a date/time window; all current members post within it (short post + link to landing/app); amplifies reach and signals “we’re live” |
| First real initiatives on the platform (content) | ☐ | So new visitors see real use, not empty state |
| Optional: Blog or updates (vision, progress, stories) | ☐ | Can be a simple page or external medium/substack |
| Optional: Social or community (e.g. Discord, forum) | ☐ | Linked from onboarding and footer |
| Outreach to aligned communities / funders | ☐ | When you’re ready to grow deliberately |

---

## 7. Quick Reference — Key Documents

| Document | Location | Purpose |
|----------|----------|---------|
| **This doc** | ZeroSeedSK/LAUNCH_CHECKLIST.md | Launch & growth task list; collaborator “start here” pointer |
| **Structural plan & product roadmap** | ZeroSeedSK/ZeroSeed_Report_v2.md | What Zero Seed is; product/infra/policy/governance roadmaps |
| **Vision** | ZeroSeedSK/ZeroSeedVisionDraft.md | Deeper vision, why now, principles |
| **Production readiness** | zeroseed/PRODUCTION-READINESS.md | Legal, security, i18n, a11y, deployment checklist |
| **App repo (run locally, contribute)** | zeroseed/README.md | How to run and contribute to the app |
| **Landing site** | zeroseed_website/ | Public landing page (deploy and wire links) |

---

*Keep this doc updated as you ship. When something’s done, tick it; when something new appears, add it. The garden gets tended one row at a time.*
