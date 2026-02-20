# Zero Seed: Launch Checklist

Track tasks needed to **launch** and **grow** Zero Seed. Update as items are completed or new tasks arise.

**Last updated:** February 2025

---

## How to use this doc

- **Sections** — grouped by theme (Website, Onboarding, Product, etc.).
- **Checkboxes** — mark when done; add rows as needed.
- **Links** — point to Vision, Report, Production Readiness, and repos.
- **Product features** — full roadmap is in **ZeroSeed_Report_v2.md** Part B and the **zeroseed** app repo. This doc covers launch- and growth-related tasks only.

---

## 1. Website (Landing / zeroseed_website)

Vision, principles, platform teaser, and ways to join or get in touch.

| Task | Status | Notes |
|------|--------|--------|
| Deploy landing page (live URL) | ☐ | e.g. zeroseed.org |
| Point “Explore the Platform” to real app URL | ☐ | Currently `href="#"` |
| Point “Read the Vision” to vision/paper | ☐ | ZeroPaperDraft.md or published page |
| Add and verify contact form | ☐ | Email or form backend so visitors can reach you |
| Footer links: Platform, Vision, GitHub | ☐ | Replace placeholders with real URLs |
| Optional: Analytics (privacy‑respecting) | ☐ | e.g. Plausible, Fathom |
| Optional: Favicon, meta description, Open Graph | ☐ | Sharing and SEO |

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

## 3. Product (App — zeroseed)

**Full roadmap:** ZeroSeed_Report_v2.md Part B. **Production readiness (legal, security, i18n):** zeroseed/PRODUCTION-READINESS.md.

Launch-oriented tasks only.

| Task | Status | Notes |
|------|--------|--------|
| Production deployment (backend + frontend) | ☐ | Hosting, env, DB (PostgreSQL when ready) |
| Auth in production (Google OAuth + JWT) | ☐ | Callback URLs, secrets, FRONTEND_URL / BACKEND_URL |
| Landing "Explore the Platform" points to app | ☐ | Website and app both live for launch |
| Privacy policy & terms | ☐ | Or placeholders; see PRODUCTION-READINESS.md §1 |
| Basic security | ☐ | HTTPS, CORS, env vars, no secrets in frontend; §3 |
| Error tracking / monitoring | ☐ | e.g. Sentry; optional |

Full feature list (documents, deltas, propose-merge, nodes): ZeroSeed_Report_v2.md Product roadmap; track in issue tracker or dev doc.

---

## 4. Governance & Operations

| Task | Status | Notes |
|------|--------|--------|
| Document “who decides what” (product, protocol, stewardship) | ☐ | Report §9.4; make easy to find |
| Code of conduct & moderation policy | ☐ | Report §9.3; PRODUCTION-READINESS.md |
| Funding / sustainability | ☐ | Multiple backers; avoid single-source dependency (Vision) |
| Where to report bugs or suggest features | ☐ | GitHub issues, contact form — linked from app and website |

---

## 5. Research & Learning

*Research plan: 7–10 interviews with thinkers/doers across geographies (motivations, ideation, action, tooling gaps); optional prototype feedback in final 5–10 min; target end of March. See full Research Plan for participants, questions, and areas to capture.*

| Task | Status | Notes |
|------|--------|--------|
| Synthesize research and feed into Zero Seed | ☐ | Map findings (motivations, ideation/action, tooling gaps, friction) into roadmap, messaging, onboarding |
| Document how research informs the initiative | ☐ | Where findings live, who owns synthesis, how they flow into roadmap/vision/positioning |

---

## 6. Growth & Movement

| Task | Status | Notes |
|------|--------|--------|
| Soft launch on LinkedIn (coordinated timing) | ☐ | Agree date/time window; all current members post (short post + link to landing/app) |
| First real initiatives on the platform | ☐ | Content so new visitors see real use |
| Optional: Blog or updates | ☐ | Vision, progress, stories — simple page or external |
| Optional: Social or community | ☐ | e.g. Discord, forum — linked from onboarding and footer |
| Outreach to aligned communities / funders | ☐ | When ready |

---

## 7. Quick Reference — Key Documents

| Document | Location | Purpose |
|----------|----------|---------|
| This doc | ZeroSeedSK/LAUNCH_CHECKLIST.md | Launch & growth tasks; collaborator “start here” pointer |
| Structural plan & product roadmap | ZeroSeedSK/ZeroSeed_Report_v2.md | What Zero Seed is; product/infra/policy/governance |
| Vision | ZeroSeedSK/ZeroSeedVisionDraft.md | Vision, why now, principles |
| Production readiness | zeroseed/PRODUCTION-READINESS.md | Legal, security, i18n, a11y, deployment |
| App repo | zeroseed/README.md | Run locally, contribute |
| Landing site | zeroseed_website/ | Public landing page |

---

Update this doc as tasks are completed or added.
