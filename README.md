# Commodity Factor-Carry Strategies

This repository contains all the code for my thesis on commodity factor-carry strategies. The [project report](project_report.pdf) can be found in this repository as well.

# Project Abstract

This thesis investigates the potential of roll-yield, also known as commodity Carry, to enhance the risk-return characteristics of traditional commodity factor strategies. This thesis utilizes backtests and OLS regressions to provide empirical evidence that information on the shape of the futures curve has the ability to simultaneously increase the returns and decrease the risk of commodity factor strategies. Furthermore, these enhanced strategies generate an abnormal return that cannot be explained by the growth in the commodity market or returns to basic commodity factor strategies. Nonetheless, there is no conclusive evidence that commodity Carry is the theoretical reason behind the improved risk-return characteristics of these strategies. The results presented in this thesis suggest that commodity factor strategies should not only invest in nearest maturity contracts, but also consider other maturities along the futures curve. On top of that, the enhanced commodity factor strategies proposed in this thesis display little to no correlation with equity and bond markets and are resistant to periods of high financial stress. Therefore, these strategies could also be used in the wider context of portfolio management to optimize traditional portfolios.

# File Overview

the `/trading_strategies` folder contains the different files used for this project. The files were built and executed in the following order:

1. `data_collection.ipynb`: script to fetch data on commodity futures from Refinitiv
2. `data_cleaning.ipynb`: basic EDA and transformation of futures price data into continuous future chain data
3. `base_carry_strategy.ipynb`: construction and backtest of benchmark strategy
4. `trading_strategies.ipynb`: construction and backtests of trading strategies under investigation
5. `analysis.ipynb`: analysis of the benchmark and trading strategies
