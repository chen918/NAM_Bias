This file contains several R scripts for the simulation study of the paper "Influence of Multiple Network Structures on Bayesian Estimation of Peer Effects and Statistical Power for Generalized Linear Network Autocorrelation Models". Each script forms the standalone file with data generation and model estimation using Bayesian approach.
The R scripts heading with "sub_" are for the analysis of the impact of the number of independent sub-networks on estimating rho.
The R scripts heading with "sub_connected" are for the analysis of the impact of the number of limited connected sub-networks on estimating rho.
The R scripts heading with "wt_" are for the analysis of the impact of the variation of the edge weights across the weighted network on estimating rho.
The R scripts heading with "rec_" are for the analysis of the impact of the levels of reciprocity in a directed network on estimating rho.
The R scripts heading with "den_" are for the analysis of the impact of the network density on estimating rho.
The R scripts heading with "single_" are for the analysis of the impact of the network size and density on estimating rho for a single network with the same size and total number of edges as the networks consisting of sub-networks.

Notably, only for scripts heading with "wt_" which study the impact of the variation of the edge weights across the weighted network on estimating rho, edges were generated from gamma distributions. For others, edges were generated from Bernoulli distributions with equal probability.

The script names end with "linear", "binary" and "Poisson" are for the linear, binary and Poisson network autocorrelation model, respectively. 
