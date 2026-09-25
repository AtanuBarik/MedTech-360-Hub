# MedTech 360 Hub

A role-aware MedTech intelligence and decision-support prototype for Evalueserve client demonstrations.

## Experience flow

1. **Login** — Enterprise SSO or username/password demo entry
2. **Role** — Executive Leadership; Product & Portfolio; Marketing, Branding & Commercial Excellence; Strategy & Business Development; Medical & Clinical Affairs / R&D & Innovation
3. **Domain** — Immunodiagnostics; Diabetes Monitoring & Blood Glucose Monitoring; Eye Health; Orthopedics & Sports Medicine; Advanced Wound Management; Clinical Laboratory Services
4. **Access** — Hub Owner, Contributor, Viewer
5. **Dashboard** — Role- and domain-aware intelligence modules plus an embedded AI copilot prototype

## Five intelligence workstreams

- Market & Competitive Intelligence
- Customer, Clinical & Research Insights
- Product & Innovation Strategy
- Pricing, Reimbursement & Commercial Excellence
- Growth, Portfolio & Corporate Strategy

The workstream taxonomy is tailored by client role. The prototype also adds policy/regulatory signal monitoring, digital/AI opportunity themes, ecosystem/partner views, and action-oriented signal cards where relevant.

## Research grounding

The prototype includes selected public-source signals from FDA, CDC, National Eye Institute, AAOS and CMS. Any dashboard score, opportunity index, trend score or other value marked **Illustrative** is demo-only and should be replaced by project research before client use.

## Security note

This repository is a static front-end prototype. The SSO and username/password screens demonstrate the desired UX only; they do **not** implement production authentication or authorization. Production deployment should connect to an enterprise identity provider (for example Microsoft Entra ID / Okta / Google Cloud Identity) and enforce access controls server-side.

## Run

Open `index.html` directly, or enable GitHub Pages for the repository and publish from the `main` branch.
