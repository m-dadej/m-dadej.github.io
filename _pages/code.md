---
layout: archive
title: "Code and software"
description: "Open-source software by Mateusz Dadej, including MarSwitching.jl — a Julia package for Markov switching (regime-switching) dynamic models, published in the Journal of Open Source Software."
permalink: /code/
author_profile: true
---

## MarSwitching.jl — Markov switching models in Julia

[MarSwitching.jl](https://github.com/m-dadej/MarSwitching.jl) is a **Julia package for estimating
Markov switching dynamic models**, also known as **regime-switching models**. These are models
whose parameters change across unobserved states of the world — useful whenever an economic or
financial time series behaves differently in, say, expansions and recessions, or in calm and
turbulent markets.

The package supports time-varying transition probabilities, mixture and vector autoregressive
specifications, simulation, and maximum likelihood estimation. It is listed in the general
registry of Julia packages (the equivalent of R's CRAN or Python's PyPI) and is published in the
[Journal of Open Source Software](/publications/marswitching-jl-julia-markov-switching/).

Bogumił Kamiński, author of [DataFrames.jl](https://github.com/JuliaData/DataFrames.jl), wrote
about the package in his post
["Advanced econometrics with Julia"](https://bkamins.github.io/julialang/2023/12/22/mars.html).

## stooq.pl wrapper — Polish market data

[A set of functions for downloading market data from stooq.pl](https://github.com/m-dadej/Downloading-and-aggregating-stocks).
Mostly useful for **Polish stock market data**, which foreign sources cover poorly — Yahoo
Finance and Python's `yfinance`, for instance, have limited coverage of the Warsaw Stock Exchange.

## Replication code

- [Agent-based model of a banking sector](https://github.com/m-dadej/agent-based-modelling-banking) — R code reproducing the model in [this paper](/publications/agent-based-modelling-banking-shocks/).
- [Systemic risk and financial connectedness](https://github.com/m-dadej/robust_fragile) — code for the working paper of the same name, listed on my [publications page](/publications/).
