# BUILD BLUEPRINT — ECON1626 A3
## "The Distribution Problem" — Australia's AI Future, 2025–2030

> Approved analytical spine. Read alongside `KNOWLEDGE_BASE_A3.md` and `RESEARCH_EVIDENCE_BASE_A3.md`.
> Signature concept = **the distribution gap**; signature mechanism = **the concentration ratchet**.

---

## 1. Thesis (Option A — approved)
Australia gets a real AI productivity dividend (PC 2025: MFP >2.3%, ~$116bn over the decade). The contested question is **who captures it**. On status-quo policy the dividend flows to capital + complemented high-skill labour, opening **the distribution gap** — the wedge between the dividend AI generates and the share reaching middle-skill labour. Falsifiable: labour share <~57% OR Gini >0.31 by 2028 = gap open.

**Signature mechanism — the concentration ratchet:** adoption rises with firm size/data (OECD 2025) → data-rich incumbents capture the dividend first → reinvest in data/model advantage → moat deepens, SMEs can't reach parity → market + spatial concentration (CSIRO/TCA 2023) → labour share falls *structurally*. The ratchet is why the gap doesn't self-correct, and why the cure targets its input (data access), not its symptom (inequality).

---

## 2. Four channels (mechanism-first; industry structure = the A2 gap)
1. **Tasks** — codifiable/routine tasks substitutable (Autor et al. 2003); JSA 2025 puts automation potential highest at ANZSCO level 4 (General/Accounting Clerks); ILO WP140 data-entry ~0.70. Equity: women ~70% of clerical (ABS 2024).
2. **Wages** — automation reduces labour share (A&R 2019) → dividend to capital + high-skill. Counter-mechanism: GenAI lifts low-skill productivity 14–35% (Brynjolfsson 2023) → can *compress* premium. Access decides direction. Link still "intact" (PC 2023) but real wages ~6% below 2020 peak (ABS 2025).
3. **Employment** — displacement vs reinstatement race; "so-so technology" worst case (A&R 2019). Currently **latent** in AU: only 12 firms cited GenAI in 2024 retrenchments (JSA 2025); McKinsey 1.3m = modelled potential.
4. **Industry structure / concentration ratchet** — the channel that locks the gap in (see §1).

---

## 3. Three scenarios (calibrated — research §6)
| Scenario | Productivity anchor (SOURCED) | Distribution (sourced + tagged ASSUMPTION) |
|---|---|---|
| Baseline "Drift" | PC 2025: MFP +2.3% / +$116bn | Labour share drifts from ~59% (Treasury 2017); Gini ~0.307, wealth Gini 0.606 (ABS); gains cluster Sydney/Melbourne (CSIRO/TCA). Displacement = ASSUMPTION calibrated to JSA. |
| Upside "Active Transition" | TCA/Microsoft 2023: up to $115bn/yr | Reinstatement keeps pace (A&R 2019); reskilling re-absorbs (effectiveness = ASSUMPTION); data-access → SME parity → ratchet jammed. |
| Downside "Concentration" | RBA 2025 ~0.7% + A&R "so-so tech" | Labour share <57% (ASSUMPTION); Gini >0.31 (ASSUMPTION); A&R 2020 robot elasticities −0.2pp/−0.42% (US proxy, tagged). |

**Change-our-mind benchmarks:** (a) labour share <57% / Gini >0.31 by 2028 → downside; (b) net new middle-skill tasks in JSA ad-share → augmentation case; (c) MFP <0.5% (PC $26bn floor) → dividend itself in doubt.

---

## 4. Policy playbook (Coasean-Berg)
Frame: assign rights over the ratchet's input (data) + keep AI-input markets contestable — **not** redistribution (Coase 1960; PC 2025 "last resort").

| Lever | Channel | Mechanism | Agency / frame | KPI |
|---|---|---|---|---|
| Data-access/portability right (extend CDR) | Industry structure | Lowers data moat → jams ratchet | ACCC; CDR | SME core-use AI ≥ large-firm by 2030 |
| Competition enforcement on AI inputs | Industry structure/wages | Prevents incumbent lock-in | ACCC; PC | HHI stable in AI-input markets |
| Outcome-tied reskilling | Tasks/employment | Accelerates reinstatement | DEWR/JobTrainer; JSA | % re-employed at ≥ prior wage in 18mo |
| (No AI levy/transfer) | — | Deliberately excluded — Berg-aligned | — | — |

**Risks + mitigations:** (1) privacy/transaction cost → tiered portable consent (Berg 2018); (2) regulatory drag → ex-post last-resort (PC 2025); (3) reskilling without outcomes → outcome-tied funding + JSA monitoring.
**Political economy:** incumbents = concentrated incentive to block data-access; SMEs/displaced = diffuse. Equity: women ~70% of exposed roles; CBA repositioning case shows ratchet in real time.

---

## 5. Interactive component map (each does economic work)
| Section | Component | Work |
|---|---|---|
| Landing | Animated distribution-gap hero (diverging dividend vs labour lines) | Thesis in one image |
| Channels 1–3 | ANZSCO exposure explorer | Shows *why* middle-skill clerical is the locus |
| Channel 4 | Concentration-ratchet simulation (period stepper + data-access toggle) | Visualises the signature mechanism + its cure |
| Scenarios | **Policy-lever wargame (centrepiece)** | Reader tests the mechanism; trajectory snaps baseline/upside/downside vs benchmark lines |
| Playbook | Channel→lever matrix | Policy is mechanism-targeted, not a wishlist |
| Methods | Assumption-tag hovers | Satisfies "every number sourced or tagged" + AI disclosure |

## 6. Word budget (~2000 ±10%)
Landing 150 · Channels 700 · Scenarios 500 · Playbook 450 · Methods 200.

## 7. Build/process
Self-contained `forecast.html` (vanilla JS + inline SVG; Google Fonts only). ≥10 meaningful commits. `README.md` with navigation + reproduction notes. Renders on GitHub Pages from repo root.
