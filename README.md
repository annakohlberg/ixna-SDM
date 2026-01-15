# ixna-SDM

This repository can be used to replicate the analyses from Kohlberg et al. 2025. The code provided here models the current and projected distribution of a temperate forest-dependent species, the varied thrush (_Ixoreus naevius_), but can be tailored to presence-absence data for other species of interest.

**main-SDM** is an Rmarkdown script that employs boosted regression trees for species distribution modeling. This script will need to be run first to create objects needed for **gams** and **hab-suitability**.

**gams** is an R script to fit generalized additive models (GAM) to assess marginal effects of predictor variables. We fit two versions of GAM to view both unadjusted effects and marginal effects of each predictor in isolation.

**hab-suitability** is a Rmarkdown script used to illustrate and quantify the probability and magnitude of habitat suitability degradation under future climatic water deficit scenarios.

**det-probability** is an R script to run an intercept-only occuppancy model to estimate how many weeks of sampling are required to detect the varied thrush at an ARU, given the species is present.
