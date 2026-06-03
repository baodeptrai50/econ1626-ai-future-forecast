# The Distribution Problem — Australia's AI Future, 2025–2030

An interactive economic forecast for **ECON1626 (Economics of AI, RMIT)**, Assignment 3.

**Live site:** `https://baodeptrai50.github.io/econ1626-ai-future-forecast/forecast.html`

---

## The argument in one line
Australia will get a real AI productivity dividend (PC 2025: MFP > 2.3%, ~$116bn over the decade). The contested question is **who captures it**. On status-quo policy the dividend flows to capital and complemented high-skill labour, opening **the distribution gap** — driven by *the concentration ratchet*, through which data-rich incumbents compound their advantage. The gap is a policy choice, and the policy is Coasean: assign the data-access right, don't redistribute the dividend.

## How to read it
The site is a single scrolling essay (~1,900 words) in six parts, mirroring the long-form forecast format of [ai-2027.com](https://ai-2027.com):

| # | Section | Interactive component |
|---|---------|-----------------------|
| 00 | **Thesis** | Animated distribution-gap chart (dividend vs labour share) |
| 01 | **Four channels** — tasks · wages · employment · industry structure | **Exposure explorer** — automation vs augmentation by occupation |
| 02 | **The concentration ratchet** | **Ratchet simulation** — run 2025–2030, toggle the data-access right |
| 03 | **Three scenarios** | **Policy wargame** — move three levers, watch the labour-share trajectory vs the 57% benchmark |
| 04 | **Policy playbook** | **Channel → lever matrix** — click a channel to see the lever that targets it |
| 05 | **Methods & references** | **Source/assumption tags** — hover any underlined figure |

**Reading the figure tags:** a **solid gold underline** = a number sourced to a named study or official dataset; a **dotted red underline (≈)** = an explicit, calibrated assumption. Hover (or tap) for the citation.

## Data & evidence
Tier-1 and official Australian sources throughout — Jobs and Skills Australia (2025), the Productivity Commission (2023, 2025), ABS, Treasury, RBA, OECD — plus the core task-economics literature (Autor, Levy & Murnane 2003; Acemoglu & Restrepo 2019, 2020; Brynjolfsson, Li & Raymond 2023). US estimates (Eloundou et al. 2024; A&R robot elasticities) are flagged as proxies. Full reference list in §05.

## AI-tool disclosure
AI tools were used to **structure, source-check and pressure-test** the argument and to build the interactive components. The economic reasoning, scenario design, calibration and policy logic are the author's own. (Per the assignment brief: AI is used to deepen and sharpen, not to one-shot.)

## Reproducing / running locally
The site is a **single self-contained file** with no build step and no external JavaScript dependencies — only Google Fonts via CDN. Everything (charts, simulation, wargame) is hand-written vanilla JS with inline SVG, so it renders identically offline.

```bash
# clone, then just open the file — or serve it:
python3 -m http.server 8000
# visit http://localhost:8000/forecast.html
```

## Deploying to GitHub Pages
1. Push `forecast.html` and `README.md` to the repo root.
2. **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / `root` → Save.**
3. Wait ~1 minute; the site goes live at the URL above.

## Repository structure
```
econ1626-ai-future-forecast/
├── forecast.html      # the interactive forecast (essay + 6 components)
├── README.md          # this file
└── BLUEPRINT_A3.md    # the approved analytical spine (process documentation)
```

## Methods note
A near-term horizon (2025–2030) is chosen so the forecast can extrapolate credibly from observed adoption/exposure data while still capturing structural change. Scenarios are calibrated to sourced productivity anchors; distribution outcomes mix sourced data with tagged assumptions, all disclosed in §05. The wargame's model interpolates labour-share, Gini, displacement and productivity outcomes between the three calibrated scenarios as a function of three policy levers — illustrative, not predictive.
