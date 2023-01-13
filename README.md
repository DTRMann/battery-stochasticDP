# battery-stochasticDP

This is a learning project for dynamic programming (DP) to develop hands-on experience in designing a simple battery optimization implementation, 
and then working up to a stochastic DP solution that supports an arbitrary number of stochastic variables. A single 24-hour period is used for each model.

The SimpleStorageArbitrage script is a deterministic algorithm that maximizes energy arbitrage. 

The StoreageArbitrageStochasticPV script determines the optimal battery dispatch path with one stochastic variable, PV generation.

The StorageOpt_StochasticPVandRTprices script determines the optimal battery dispatch path with two stochastic variables - PV generation and price. The approach
is generalized to accommodate an arbitrary number of stochastic variables.

