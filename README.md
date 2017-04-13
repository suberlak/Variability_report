# Variability_report

A repository for a technical paper, that together  with a [Faint Pipeline Report](https://github.com/suberlak/Faint_pipeline_report) accompany the data-driven research paper on SDSS Stripe 82 Summer 2013 reprocessing [SDSS_2016_paper](https://github.com/suberlak/SDSS_2016_paper/).
We describe ways to distinguish variability from noise, ranging from time-domain (chi2, BIC, Bayesian parametrization) to frequency-domain (Lomb-Scargle periodogram). 

Code used to make figures in this report is in  the [SDSS_S82_FP_research](https://github.com/suberlak/SDSS_S82_FP_research) repo. 

In particular : 

Research    |   Notebook 
------------|------------
Chi2 tests, completeness curve | Variability_time_completeness_curve
Benchmarking AstroML 5.8 code: how number of bootstraps, number of points affect speed of execution | Variability_timeit_AstroML
Frequency : investigating gridding choice | Variability_frequency_grid

