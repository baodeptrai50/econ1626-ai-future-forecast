# The Distribution Problem — Australia's AI Future, 2025–2030

An interactive economic forecast for **ECON1626 (Economics of AI, RMIT)**, Assignment 3.

**Live site:** `https://baodeptrai50.github.io/econ1626-ai-future-forecast/forecast.html`

---

## The argument in one line
Australia will get a real AI productivity dividend (PC 2025: MFP > 2.3%, ~$116bn over the decade). The contested question is **who captures it**. On status-quo policy the dividend flows to capital and complemented high-skill labour, opening **the distribution gap** — driven by *the concentration ratchet*, through which data-rich incumbents compound their advantage. The gap is a policy choice, and the policy is Coasean: a data-access right makes *prediction* contestable but not *intervention*, so make the **relationship layer** contestable — account switching and payment-mandate portability that move the customer's default interface — rather than redistribute the dividend.

## How to read it
A single scrolling essay (~2,000 words) in six parts, long-form-forecast style, with each interactive doing genuine economic work (not decoration):

| # | Section | Interactive component |
|---|---------|-----------------------|
| 00 | **Thesis** | **Scrollytelling chart** — the distribution gap opens as you scroll, with a live `$0 → $116bn` counter |
| 01 | **Four channels** — tasks · wages · employment · industry structure | **Mechanism map** (animated causal signal-flow; toggle the data-access right to re-route it) + **exposure explorer** (automation vs augmentation by occupation) |
| 02 | **The concentration ratchet** | **Ratchet simulation** — a mechanical ratchet-and-pawl (pawl = the data-access right) running alongside the moat chart, 2025–2030 |
| 03 | **Three scenarios** | **Dividend engine** — a canvas particle-flow of the $116bn into Capital / High-skill / Middle-skill, driven by three policy levers, with a live labour-share trajectory and **shareable scenario URLs** |
| ★ | **Choose the 2030** | **Morphing finale dial** — slide between the two futures; numbers, mood and narrative respond |
| 04 | **Policy playbook** | **Channel → lever matrix** — click a channel to see the lever that targets it |
| 05 | **Methods & references** | **Source/assumption tags** — hover any underlined figure |

**Reading the figure tags:** a **solid gold underline** = a number sourced to a named study or official dataset; a **dotted red underline (≈)** = an explicit, calibrated assumption. Hover (or tap) for the citation.

## The real-world anchor — a natural experiment
Rather than a single firm's layoffs, the playbook is anchored on Australia's **Consumer Data Right (CDR)** — a statutory data-access right, live in banking since 2020, in the exact sector the forecast studies. An industry review (ABA/Accenture) put active data-sharing at just **0.31%** of bank customers by end-2023, after ~A$1.5bn in compliance spend, prompting the government's 2024 reset (Treasury 2022, 2024). Yet the CDR has not failed — it is growing fast as a data pipe, now powering mortgage broking and alternative credit scoring (ACCC 2025). That is the lesson: the CDR makes *prediction* contestable but not *intervention* — it ports the transaction signal, not the customer's default interface (primary account, payroll, direct debits) where AI turns a prediction into immediate retention, pricing or cross-sell. The ratchet's pawl is the relationship anchor, which a data right cannot port — so the lever targets the relationship layer (account switching + portable payment mandates), complementing the data right. The current banking structure (the Big Four hold ~73% of mortgages and resident deposits, ~70% of resident assets, APRA April 2026) is the ratchet's live state.

## Data & evidence
Tier-1 and official Australian sources throughout — Jobs and Skills Australia (2025), the Productivity Commission (2023, 2025), the ACCC (2020, 2025), ABS, Treasury, RBA, APRA, OECD — plus the core task-economics literature (Autor, Levy & Murnane 2003; Acemoglu & Restrepo 2019, 2020; Brynjolfsson, Li & Raymond 2023) and the institutional framing of Coase (1960) and Berg (forthcoming). US estimates (Eloundou et al. 2023; A&R robot elasticities) are flagged as proxies. Full reference list in §05.

## Accessibility & theming
A light/dark theme toggle sits in the header (default follows the system preference; the choice persists where the browser allows it). The site honours `prefers-reduced-motion`: the marching signal flows, particle engine and scroll/load animations are stilled, with static fallbacks drawn so every chart still reads. Interactive controls are keyboard-focusable and charts carry `aria-label` descriptions.

## AI-tool disclosure
AI tools were used to **structure, source-check and pressure-test** the argument and to build the interactive components. The economic reasoning, scenario design, calibration and policy logic are the author's own. (Per the assignment brief: AI is used to deepen and sharpen, not to one-shot.)

## Reproducing / running locally
A **single self-contained file** with no build step and no external JavaScript dependencies — only Google Fonts via CDN. Charts, simulation, engine and finale are hand-written vanilla JS with inline SVG/Canvas, so it renders identically offline.

```bash
# clone, then just open forecast.html — or serve it:
python3 -m http.server 8000
# visit http://localhost:8000/
```

## Deploying to GitHub Pages
1. Push `forecast.html` and `README.md` to the repo root.
2. **Settings → Pages → Source: Deploy from a branch → `main` / `root` → Save.**
3. Wait ~1 minute; the site goes live at the repository's Pages URL.

## Repository structure
```
<repo>/
├── forecast.html      # the interactive forecast (essay + interactives)
├── README.md          # this file
└── BLUEPRINT_A3.md    # the analytical spine (process documentation)
```

## Methods note
A near-term horizon (2025–2030) lets the forecast extrapolate from observed adoption/exposure data while still capturing structural change. Scenarios are calibrated to sourced productivity anchors; distribution outcomes mix sourced data with tagged assumptions, all disclosed in §05. The dividend engine and labour-share trajectory interpolate outcomes between the three calibrated scenarios as a function of three policy levers — illustrative, not predictive.
