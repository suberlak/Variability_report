# Variability_report

A repository for a technical paper, that together  with a [Faint Pipeline Report](https://github.com/suberlak/Faint_pipeline_report) accompany the data-driven research paper on SDSS Stripe 82 Summer 2013 reprocessing [SDSS_2016_paper](https://github.com/suberlak/SDSS_2016_paper/).
We describe ways to distinguish variability from noise, ranging from time-domain (chi2, BIC, Bayesian parametrization) to frequency-domain (Lomb-Scargle periodogram). 

Code used to make figures in this report is in  the [SDSS_S82_FP_research](https://github.com/suberlak/SDSS_S82_FP_research) repo. 

In particular : 

Research    |   Notebook 
------------|------------
Chi2 variance simulation  | Variability_chi2_test_AstroML 
Weighted interquartile range, used in calculating the mean sigma | Variability_weighted_interquartile_range 
What quantities are calculated for p(sigma) | Variability_descriptors_of_p_sigma 
Chi2 tests, completeness curve | Variability_time_completeness_curve
Benchmarking AstroML 5.8 code: how number of bootstraps, number of points affect speed of execution | Variability_timeit_AstroML
Frequency : investigating gridding choice | Variability_frequency_grid
Frequency : choosing the best grid | Variability_frequency_grid_solution
Simulating the estimate of periodogram peak height from AstroML eq. 10.49 | Variability_frequency_AstroML_chap-10 
Comparing BIC to AIC in the periodogram context : AstroML Fig.10.15 | Variability_compare_BIC_vs_AIC_AstroML_Fig10-15 


