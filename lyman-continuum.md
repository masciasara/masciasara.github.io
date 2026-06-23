---
layout: page
title: Lyman Continuum Leakers
subtitle: The galaxies that let ionizing light escape
---

## The problem

For the Universe to have reionized, ionizing photons had to escape from the galaxies that produced them. But ionizing radiation -- light at wavelengths shorter than 912 Å -- is easily absorbed by neutral hydrogen. Most galaxies hold onto that light entirely. The ones that don't are called **Lyman continuum leakers**.

Finding them, and understanding why they leak, is central to solving the reionization puzzle. But there is a catch: at the redshifts where reionization actually happened (z ≥ 4.5), the intergalactic medium is too opaque to detect ionizing photons directly. They are absorbed before they reach us.

The solution is to study **low-redshift analogs** -- galaxies at z ~ 0.3–0.4 where LyC emission can be directly detected -- and use them to calibrate indirect diagnostics: observable properties that correlate with the escape fraction. Then we apply those diagnostics to high-redshift galaxies to infer their ionizing output.

---

## What makes a galaxy leak

Several properties correlate with high LyC escape fractions:

- **Compact morphology** — small, dense galaxies with intense, concentrated star formation
- **High ionization** — strong [O III] emission relative to [O II], tracing density-bounded HII regions
- **Blue UV slopes** — indicating young stellar populations and low dust content
- **High Lyman-alpha equivalent width** — Lyα and LyC photons share similar escape conditions
- **High star formation rate surface density** — stellar feedback can carve low-density channels through the ISM

No single indicator is a perfect predictor. The escape fraction depends on the three-dimensional geometry of the gas — which we cannot observe directly. This is why multivariate approaches matter.

---

## My work

### LyC leakers at z ≥ 4.5 with JWST

Using early JWST/NIRSpec observations from the GLASS-JWST program, I studied 29 gravitationally lensed galaxies at 4.5 ≤ z ≤ 8 in the Abell 2744 field. I measured their physical and spectroscopic properties — stellar masses, UV slopes, sizes, emission line ratios — and compared them to low-redshift confirmed LyC leakers.

The result: these galaxies are low-mass (log M★ ~ 8.5 M☉), compact (re ~ 0.3–0.5 kpc), blue (β ~ −2.1), and highly ionized. Their properties overlap almost entirely with those of known leakers at low redshift. Using an empirical relation calibrated on the LzLCS+ sample, I predicted escape fractions for 24 sources — more than 80% have fesc > 0.05, with an average of ~0.12.

<!-- Add figure: O32 vs EW(Hβ) diagnostic plot, or predicted fesc vs size -->
<!-- ![Caption](/assets/images/glass_diagnostics.png) -->

**Mascia et al. 2023** · A&A, A221 · [doi:10.1051/0004-6361/202245152](https://doi.org/10.1051/0004-6361/202245152)

---

### Faint galaxies at 6 ≤ z ≤ 9: how much did they contribute?

The GLASS sample was small. To put those conclusions on firmer ground, I extended the analysis to 70 spectroscopically confirmed star-forming galaxies from the CEERS survey, combined with 12 sources from other early JWST programs — 82 sources total at 6 ≤ z ≤ 9.

The galaxies are compact (re ~ 0.4 kpc), blue (β ~ −2.17), and have modest predicted escape fractions — mean fesc ~ 0.13, median ~ 0.08. Only 20% have fesc > 0.2. I also measured their ionizing photon production efficiency from [O III] emission, finding a mean log ξion ~ 25.27.

The key result: galaxies currently characterizable with JWST — those brighter than M1500 = −18 — contribute **less than 35% of the total ionizing budget**. The bulk of reionization was likely driven by fainter, lower-mass sources we cannot yet fully characterize. Pushing two to three magnitudes deeper, using gravitational lensing as a tool, will be essential.

<!-- Add figure: ionizing budget as a function of M1500 -->
<!-- ![Caption](/assets/images/ceers_ionizing_budget.png) -->

**Mascia et al. 2024** · A&A, A3 · [doi:10.1051/0004-6361/202347884](https://doi.org/10.1051/0004-6361/202347884)

---

### Does morphology matter? Mergers and LyC escape at z = 5–7

A common assumption is that galaxy mergers — by disrupting gas distributions and creating anisotropic channels — could facilitate LyC escape. I tested this directly on a sample of 436 spectroscopically confirmed galaxies at 5 ≤ z ≤ 7, drawn from EIGER, CEERS, and JADES.

I classified galaxy morphologies using Gini coefficient, M20, and asymmetry parameters measured from JWST/NIRCam F115W imaging, identifying merger candidates through established criteria. I also developed a revised survival analysis framework — using Cox proportional hazards models calibrated on a subsample of 51 LzLCS+ galaxies that are genuine analogues of reionization-era sources.

The result is clear: **neither fesc nor ξion show a significant correlation with merger signatures**. Most galaxies in the sample are compact and symmetric. The merger fraction is low, and high fesc sources are equally distributed between mergers and non-mergers. LyC escape at these redshifts appears to be governed by compactness and star formation intensity — internal properties — rather than by morphological disturbances.

<!-- Add figure: Gini-M20 diagram color-coded by predicted fesc -->
<!-- ![Caption](/assets/images/morphology_fesc.png) -->

**Mascia et al. 2025**

---

→ [Compact broad-line emitters](/research/broad-line-emitters)
→ [Cosmic reionization](/research/reionization)
→ [Back to Academia](/academia)

---

*Questions or collaborations welcome — [get in touch](mailto:sara.mascia@ista.ac.at).*
