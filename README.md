# Eurasian Continental Bridges: Silver Living Costs, Internal Russian Convergence, and the Great Divergence, 1738–1913

[![License: MIT](https://shields.io)](LICENSE)

This repository contains the reproducible Python/Jupyter pipeline, high-resolution figures, open-access source datasets, and LaTeX manuscript sources for the study:

> **Avtonomov, P. (2026d).** *Eurasian Continental Bridges: Silver Living Costs, Internal Russian Convergence, and the Great Divergence, 1738–1913.*

This work is the fourth study in a multi-layer empirical research cycle auditing historical market integration across Atlantic grain prices ([doi:10.5281/zenodo.24436177](https://doi.org)), Baltic Sound Toll shipping passages ([doi:10.5281/zenodo.24461586](https://doi.org)), St. Petersburg–European exchange rates ([doi:10.5281/zenodo.24498028](https://doi.org)), and the Eurasian continental corridor.

## Key Empirical Findings

* **Internal Russian Convergence (`1720s–1800s`):** In the mid-eighteenth century, Moscow's barebones silver subsistence basket (`100.1 g` Ag/year in the 1760s) stood well below Western Europe (`190–238 g`) and Qing China (`191–219 g`). Regional silver wheat prices across Novgorod–St. Petersburg, Moscow, and the Northern Dvina (Arkhangelsk) converged upward into the `0.60–0.71 g` Ag/kg range by the 1800s, bringing Moscow's silver living costs (`224.4 g` in the 1780s) into parity with Amsterdam (`207.9 g`) and Beijing (`208.0 g`).
* **Pre-Opium War Tri-Polar Eurasia (`1739–1833`, $M = 95$, Uninterpolated):** Singular value decomposition on the strictly uninterpolated seven-city panel confirms a three-way structural division even prior to the Opium Wars: the Western/Central European core (`Amsterdam` $v_1 = +0.553$, `London` $+0.464$, `Leipzig` $+0.357$, `Florence` $+0.262$), maritime southern China (`Canton` $-0.436$, `Suzhou` $-0.298$), and isolated continental northern China (`Beijing` $v_1 = +0.066$, $\mathrm{Mode~2} = +0.451$).
* **Post-1840 European Consolidation vs. Beijing Isolation:** After 1840, the four unbroken European cities coalesced into a symmetric co-moving block ($\mathrm{Var}_1 = 59.2\%$; individual shares `21.23–28.66%`), whereas continental `Beijing` decoupled almost completely (`Mode 1` share dropping from `3.97%` in `1739–1839` to `0.97%` in `1840–1913`; $v_{2,\mathrm{Beijing}} = -0.971$).
* **Two-Stage Eurasian Structural Break (`1857` vs. `1891`):** Non-parametric transition-graph scanning along the Fiedler eigenvector $\psi_2$ reveals that real living standards (*welfare ratios*) fractured first in **`1857`** ($p < 0.0001$) amid the Taiping Rebellion and mid-century industrial divergence, whereas silver-denominated consumer prices (*CPI*) broke decisively in **`1891`** ($p = 0.0084$ for $N=5$; $p = 0.0008$ for $N=7$) during global silver demonetization.

## Repository Contents

* `reproduce_eurasian_bridges.ipynb` / `reproduce_eurasian_bridges.py` — End-to-end reproducible Python script generating all summary statistics, bootstrap confidence intervals, and `300 dpi` figures.
* `Figure_1_Eurasia.png` — Eurasian silver living costs, internal Russian wheat convergence, pre/post-1840 Mode 1 shares, and transition-graph break scan.
* `Figure_2_Eurasia.png` — Tri-polar structural map of seven Eurasian cities (`1739–1913`) and real welfare ratio trajectories (`1738–1913`).
* `Eurasian_Continental_Bridges.pdf` / `main.tex` — Complete compiled preprint and LaTeX manuscript source.
* `China_1730-1933_Allen_et_al.xls`, `Moscow living standards, Korchmina Calculations for Rivista.xlsx`, `Russia_wheat_c1500-c1870.xls` — Open-access Global Price and Income History Group (GPIHG) source datasets.

## License

Code is released under the MIT License; manuscript text and figures are licensed under [CC BY 4.0](https://creativecommons.org).
