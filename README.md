# ECON1626 — AI Future Forecast: *The Two-Speed Bank*

An interactive economic web essay forecasting how artificial intelligence will reshape **Australia's financial-services industry between 2027 and 2030**.

Submitted for **ECON1626 — AI & the Economy**, RMIT University, Bachelor of Business (Finance / Online Economies).

🔗 **Live site:** [lucaswein4.github.io/econ1626-ai-future-forecast/forecast.html](https://lucaswein4.github.io/econ1626-ai-future-forecast/forecast.html)


---

## Thesis

AI will not lift Australian financial services evenly. By 2030 it will split the industry into a **two-speed** structure — a fast lane of AI-native institutions capturing the productivity windfall, and a slow lane of laggards and displaced workers left behind. Which trajectory Australia gets is being decided by **regulatory choices made now**, not by the technology itself.

## Repository contents

| File | Purpose |
|------|---------|
| `forecast.html` | The full interactive web essay — all text, styling, and live Chart.js visualisations in a single file |
| `README.md` | This file — project overview and navigation |

All charts are generated dynamically in-browser by Chart.js (loaded via CDN) within `forecast.html`; there are no separate image files to manage.

## How to read it

Open `forecast.html` in any browser, or visit the live GitHub Pages link above. The essay is structured as:

1. **Thesis** — the core claim and why it matters
2. **Capabilities → Economic Channels** — the Acemoglu–Restrepo task-based mechanism mapped onto finance
3. **Scenarios** — interactive baseline / upside / downside projections (toggle the chart)
4. **Policy Playbook** — four levers, their trade-offs and KPIs (expandable)
5. **Methods, Data & Limitations** — sources, AI-tooling disclosure, uncertainty
6. **References** — RMIT Harvard style

## Interactive features

- **Scenario toggle** — switch between the three economic trajectories and read how each plays out
- **Adoption comparison chart** — Australian vs global AI uptake in financial services
- **Policy decision tree** — expandable branches showing trade-offs and unintended consequences

Built with plain HTML, CSS and Chart.js (loaded via CDN). No build step required.

## Theoretical framework

Applies the **task-based labour-economics framework** of Acemoglu & Restrepo (2019) — decomposing AI's effect into *displacement*, *productivity*, *reinstatement* and *skill-biased* channels — and maps each onto financial-services tasks.

## Key evidence base

- Productivity Commission (2025), *Harnessing Data and Digital Technology* — ~$116B decade GDP estimate
- Broadridge (2025) & Infosys (2025) — Australian AI adoption surveys
- AFIA (2025) — finance-sector growth potential
- ASIC (2025) & APRA (2025) — regulatory positions
- Acemoglu & Restrepo (2019) — theoretical framework

## Running locally

No dependencies to install. Either double-click `forecast.html`, or serve it with `python3 -m http.server` then open `http://localhost:8000/forecast.html`.

## Hosting

The site is published via GitHub Pages from the `main` branch (root).

## AI use acknowledgement

Per RMIT academic-integrity guidelines and this assessment's open AI-use policy, generative AI assisted with source discovery, the HTML/Chart.js scaffolding, and drafting/structure. The thesis, economic argument, scenario logic, source selection and synthesis are the author's own; all factual claims were verified against the cited primary sources.

## Author

Bachelor of Business (Finance / Online Economies), RMIT University, 2026.
