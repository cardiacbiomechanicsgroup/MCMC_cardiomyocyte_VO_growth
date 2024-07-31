# MCMC_Cardiomyocyte_hypertrophy

This program analyze experimental data from animal models of volume overload to produce a Bayesian calibration of a network-like model of cardiomyocyte molecular signaling for hypertrophy.

This network model is solved using the program Netflux by the Cardiac Systems Biology Group (PI Dr. Jeffrey Saucerman). Available at https://github.com/saucermanlab/Netflux

The code runs Markov Chain Monte Carlo simulations iteratively running Netflux and estimating the likelyhood of the solutions to experimental data from animal models.

Details of the methodology is provided in Bracamonte et al. (2024) PLOS Computational Biology (doi to be defined).

Intructions:

1) Download the zip folder, uncompress in desired directory.
2) Select analysis modality.
2.1.) run_MCMC_VO: Runs an MCMC analysis of organ-scale and molecular scale data to produce the probability distribution of Cardiomyocyte Network model according to experimental data.
2.2.) run_pharmacological_cases: Generates Bayesian predictions of the effect of pharmacological interventions in the context of volume overload and infusion of growth factots.

The program runs in MATLAB 2009b or higher.
