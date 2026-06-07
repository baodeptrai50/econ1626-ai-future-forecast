# BUILD BLUEPRINT — ECON1626 A3
## "The Distribution Problem" — Australia's AI Future, 2025–2030

> Analytical spine for the delivered site (`forecast.html`) — process documentation accompanying the essay.
> Signature concept = **the distribution gap**; signature mechanism = **the concentration ratchet**.

---

## 1. Thesis
Australia gets a real AI productivity dividend (PC 2025: MFP >2.3%, ~$116bn over the decade). The contested question is **who captures it**. On status-quo policy the dividend flows to capital + complemented high-skill labour, opening **the distribution gap** — the wedge between the dividend AI generates and the share reaching middle-skill labour. Falsifiable: labour share <~57% OR Gini >0.31 by 2028 = gap open.

**Signature mechanism — the concentration ratchet:** adoption rises with firm size/data (OECD 2025) → data-rich incumbents capture the dividend first → reinvest in data/model advantage → moat deepens, SMEs can't reach parity → market + spatial concentration (CSIRO/TCA 2023) → labour share falls *structurally* (driven by technology + market power, La Cava 2019). The ratchet is why the gap doesn't self-correct. The binding input is not the data file but the **deployment/relationship layer** — the customer's default interface (primary account, payroll, direct debits) where AI turns predictions into action; CDR ports the signal, not the relationship. The cure targets contestability of that relationship layer, not data access alone, and not the symptom (inequality).

---

## 2. Four channels (mechanism-first; industry structure = the A2 gap)
1. **Tasks** — codifiable/routine tasks substitutable (Autor et al. 2003); JSA 2025 puts automation highest at ANZSCO level 4 (General/Accounting Clerks); ILO WP140 data-entry ~0.70. Equity: women ~72% of clerical (ABS Labour Force Detailed 2026); finance & insurance ~540k employed (ABS 2026).
2. **Wages** — automation reduces labour share (A&R 2019) → dividend to capital + high-skill. Counter-mechanism: GenAI gives 14% avg / 35% lowest-skill productivity gains (Brynjolfsson 2023) → *implies* compression. Access decides direction. Link still "intact" for 95% of workers (PC 2023); ABS 2023 ≈0.8pt pass-through; real wages still falling — WPI +3.3% vs CPI +4.6% to Mar 2026 (ABS 2026).
3. **Employment** — displacement vs reinstatement race; "so-so technology" worst case (A&R 2019). Currently **latent** in AU: only 12 firms cited GenAI in 2024 retrenchments (JSA 2025); McKinsey 1.3m = modelled potential.
4. **Industry structure / concentration ratchet** — the channel that locks the gap in (see §1). Live state: Big Four ~73% mortgages & resident deposits, ~70% resident assets (APRA Apr 2026).

---

## 3. Three scenarios (calibrated — research §6)
| Scenario | Productivity anchor (SOURCED) | Distribution (sourced + tagged ASSUMPTION) |
|---|---|---|
| Baseline "Drift" | PC 2025: MFP +2.3% / +$116bn | Labour share drifts from ~59% (Treasury 2017); Gini ~0.307, wealth Gini 0.606 (ABS); gains cluster Sydney/Melbourne (CSIRO/TCA). Displacement = ASSUMPTION. |
| Upside "Active Transition" | TCA/Microsoft 2023: up to $115bn/yr | Reinstatement keeps pace (A&R 2019); reskilling re-absorbs (effectiveness = ASSUMPTION); data-access → SME parity → ratchet jammed. |
| Downside "Concentration" | RBA 2025 ~0.7% + A&R "so-so tech" | Labour share <57% (ASSUMPTION); Gini >0.31 (ASSUMPTION); A&R 2020 robot elasticities −0.2pp/−0.42% (US proxy). |

**Change-our-mind benchmarks:** (a) labour share <57% / Gini >0.31 by 2028 → downside; (b) net new middle-skill tasks in JSA ad-share → augmentation case; (c) MFP <0.5% (PC $26bn floor) → dividend itself in doubt.

---

## 4. Policy playbook (Coasean-Berg)
Frame: make the ratchet's binding input — the **relationship/deployment layer**, not just data — contestable (account switching + payment-mandate portability, complementing a data-access right), and keep AI-input markets contestable — **not** redistribution (Coase 1960; Berg forthcoming; PC 2025 "last resort").

| Lever | Channel | Mechanism | Agency / frame | KPI |
|---|---|---|---|---|
| Relationship-layer contestability (account switching + portable payment mandates) + low-cost data-access right | Industry structure | CDR makes *prediction* contestable, not *intervention*; moving the relationship anchor jams the ratchet | ACCC; CDR; Treasury | Primary-account switching ↑ and SME core-use AI ≥ large-firm by 2030 |
| Competition enforcement on AI inputs | Industry structure/wages | Prevents incumbent lock-in | ACCC; PC | HHI stable in AI-input markets |
| Outcome-tied reskilling | Tasks/employment | Accelerates reinstatement | DEWR/JobTrainer; JSA | % re-employed at ≥ prior wage in 18mo |
| (No AI levy/transfer) | — | Deliberately excluded — Berg-aligned | — | — |

**Risks + mitigations:** (1) privacy/transaction cost → tiered portable consent (Berg 2018); (2) regulatory drag → ex-post last-resort (PC 2025); (3) reskilling without outcomes → outcome-tied funding + JSA monitoring.

**Real-world anchor — the CDR natural experiment (replaces the recycled CBA case):** Australia already assigned a statutory data-access right (CDR) in banking in 2020; an ABA/Accenture industry review put active uptake at **0.31%** of bank customers by end-2023, after **~A$1.5bn** compliance spend; the government reset it in 2024 (Treasury 2022, 2024). But the data layer IS now being contested — CDR powers mortgage broking + alt-credit scoring (ACCC 2025). The sharper lesson: **CDR makes *prediction* contestable, not *intervention*** — it ports the signal, not the customer's default interface (primary account, payroll, direct debits) where AI turns predictions into retention/pricing/cross-sell. The ratchet's pawl = the relationship anchor, which a data right can't port → the lever targets relationship-layer contestability (account switching + payment-mandate portability), complementing the data right, not the CDR-as-built alone.

**Political economy:** incumbents = concentrated incentive to block reform; SMEs/displaced = diffuse. Equity: women ~72% of exposed clerical roles.

---

## 5. Interactive components (each does economic work) — as built
| Section | Component |
|---|---|
| Thesis | Scroll-driven distribution-gap chart + live $0→$116bn counter |
| Channels | Animated **mechanism map** (causal signal-flow, policy re-route toggle) + ANZSCO **exposure explorer** |
| Ratchet | Mechanical **ratchet-and-pawl** wheel + moat line chart (data-access toggle) |
| Scenarios | **Dividend engine** (canvas particle-flow to Capital/High-skill/Middle-skill) + labour-share trajectory + three levers + **shareable scenario URLs** |
| ★ 2030 | **"Choose the 2030"** morphing finale dial |
| Playbook | Channel→lever matrix |
| Methods | Source/assumption hover tags + AI disclosure |
| Site-wide | Light/dark theme, `prefers-reduced-motion` fallbacks, mobile layout |

## 6. Word budget
~2,000 ±10% (delivered ≈ 2,019 prose words). Every number sourced or tagged.

## 7. Build/process
Self-contained `forecast.html` (vanilla JS + inline SVG/Canvas; Google Fonts only). Renders on GitHub Pages from repo root. Frequent, descriptive commits — not a single end-of-process upload.
