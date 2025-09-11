
<h1 align="center">Marcos Montero</h1>

<p align="center">
  <b>Engineering Manager · Staff Frontend</b><br/>
  Web & Product Teams • People & Delivery Leadership • React/Next • PostgreSQL
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/-marcos-montero"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white"></a>
  <a href="mailto:marcos.mon.rod@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-marcos-black?logo=gmail"></a>
  <img alt="Location" src="https://img.shields.io/badge/Madrid-remote--friendly-000000?logo=homeassistant&logoColor=white">
  <img alt="Focus" src="https://img.shields.io/badge/Focus-EM%20%7C%20Staff%20FE-111111">
</p>

---

### What I do (in one line)
Build **motivated teams** and **ship web products** that move business metrics — with just enough tech depth to make solid trade-offs.

---

## Highlights

- Grew and led teams **0 → 4 engineers**, put in place **hiring, onboarding, 1:1s, feedback & performance**.
- Drove a full **digital transformation** on **Next.js + PostgreSQL (Supabase/Neon)**; launched a **self-serve booking** flow generating **~€30k/week**.
- Delivery: on-time releases **~70% → 95%**, incident rate **−60%**, migration time **−40%**, UI defects **−30%**.
- Culture: quarterly **hackathons & game-based workshops** → morale up, **6 prototypes**, **2 shipped** to prod.
- Background: React/Next.js, TypeScript, Postgres, Stripe, testing, analytics. Comfortable across **product, design, and engineering**.

---

## How I lead

- **People**: hire well, set clear expectations, 1:1s, growth plans, fair reviews, succession.
- **Delivery**: roadmaps, capacity planning, risk/dependency mgmt, visible comms, predictable execution.
- **Quality**: design systems, testing strategy (unit/integration/E2E), CI/CD, perf budgets (LCP/TTI), SLOs & postmortems.
- **Collaboration**: tight loop with PM/Design/Marketing; data-informed decisions.

> I like **documents over meetings**, **design reviews over surprises**, and **small safe releases over heroics**.

---

## Tech I speak
`React` · `Next.js (SSR/ISR/RSC)` · `TypeScript` · `PostgreSQL` · `Supabase/Neon` · `Stripe` · `Node` · `Playwright/Cypress` · `GA4/Hotjar` · basic `CI/CD`

---

## Playbooks I use
- **Hiring** (scorecards, structured interviews, onboarding 30/60/90)
- **Incident response** (SEV levels, IC/Comms roles, blameless postmortems)
- **Execution** (quarterly planning, WIP limits, risk register, demo culture)
- **Team development** (career ladders for ICs/EMs, growth plans, knowledge sharing)

---

## What I’m open to
- **Engineering Manager** for web/product teams (people + delivery + quality).  
- **Staff Frontend** with cross-team impact (platform/design-system/perf).  
- Remote-first EU/UK/US-friendly.

---

### Contact
- DM on **LinkedIn**, or email **marcos.mon.rod@gmail.com**.

---

<details>
  <summary>Automation (optional): GitHub Metrics badge</summary>

Add a profile metrics card with a scheduled action:

```yaml
# .github/workflows/metrics.yml
name: Metrics
on:
  schedule: [{cron: "0 8 * * 1"}]  # weekly
  workflow_dispatch:
jobs:
  github-metrics:
    runs-on: ubuntu-latest
    steps:
      - uses: lowlighter/metrics@latest
        with:
          token: ${{ secrets.METRICS_TOKEN }}
          base: header, activity
          plugin_isocalendar: yes
          plugin_followup: yes
          plugin_traffic: yes
