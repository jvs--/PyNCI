# PyNCI
A python module for Bayesian effective connectivity inference from calcium imaging and spike train data.
Available submodules:

- SECI
- MECI 

This repo will hold the full source code upon publication until then if you are interested request access to the private repo.

## SECI
Spatial Effective Connectivity Inference (SECI) incorporates distance-dependent connectivity regularazation into known techniques that impose sparseness via L1/L2-norm in a linear non-linear poisson (LNP) cascade model. 

Two simple maximum likelihood estimation approaches with gradient decent and Newton’s method are available (SECI-l1 and SECI-l2). Furthermore, an extended hierarchical maximum a posteriori estimation approach with Metropolis-Hastings sampling is provided as well (SECI-MAP). In this approach a prior over the existence of neural connections based on euclidian distance between neurons is included into the regularization term.

## MECI
Modular Effective Connectivity Inference (MECI) uses the formulation of a modularity prior which clusters neurons into funtional modules and applies different model parameters for connections estimation within and between modules. A Gibbs sampling algorithm that dynamically re-assigns module membership and estimates a weight matrix is available.

## Getting started

## Installation

## Dependencies

## Citing PyNCI
Forthcoming:
- \[Schulze, Yoshimoto, Doya, 2019a\]
- \[Schulze, Yoshimoto, Doya, 2019b\]

## License
