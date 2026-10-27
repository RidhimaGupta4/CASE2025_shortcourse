# My work

Colab-ready notebooks for the CASE 2025 short course *AI and extremes*
(Likun Zhang, Jordan Richards and Reetam Majumder), plus one extension of my own.

| Notebook | Content |
|---|---|
| `01_deep_GPD_regression_wildfires.ipynb` | Deep quantile regression and deep generalised Pareto (peaks-over-threshold) regression for US wildfire burnt area; three models for the shape parameter ξ; LIME interpretation. Course code, annotated. |
| `02_SPQR_density_regression.ipynb` | Semi-parametric quantile regression (SPQR): conditional densities as neural-network-weighted M-spline mixtures. Course code, annotated. |
| `03_neural_Bayes_estimator.ipynb` | Simulation-trained, amortised neural Bayes estimator for Hüsler–Reiss extremal dependence, applied to annual temperature maxima. Course code, annotated. |
| `04_extension_blocked_vs_random_validation.ipynb` | **My extension:** random vs year-blocked validation of the Notebook 01 pipeline, compared like-for-like on the held-out year 2015, with climatology skill scores and 3 seeds. |
| `figures/` | Figures produced by Notebook 04 and used in the main README. |

**To run:** open a notebook in Google Colab, choose *Runtime → Change runtime type → R*
(CPU is enough), then *Runtime → Run all*. Each notebook installs its packages and
downloads its data from the original course repository.

Changes to the course code are marked **[Adapted]** inside the notebooks.
Evaluation shortcuts kept from the original course are flagged as **validation notes**.
See the main `README.md` for the extension's design, results and limitations.
