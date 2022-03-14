## Smart Beta and Portfolio Optimization

## AI for Trading Nano Project

In this project, we will build a smart beta portfolio and compare it to a benchmark index. To find out how well the smart beta portfolio did, we'll calculate the tracking error against the index. We'll then build a portfolio by using quadratic programming to optimize the weights. The code will rebalance this portfolio and calculate turn over to evaluate the performance. We'll use this metric to find the optimal rebalancing Frequency. For the dataset, we'll be using the end of day from Quotemedia.

## Smart Beta

Smart beta strategies seek to passively follow indices, while also considering alternative weighting schemes such as volatility, liquidity, quality, value, size and momentum. 

The goal of smart beta is to obtain alpha, lower risk or increase diversification at a cost lower than traditional active management and marginally higher than straight index investing. It seeks the best construction of an optimally diversified portfolio. In effect, smart beta is a combination of efficient-market hypothesis and value investing. The smart beta investment approach applies to popular asset classes, such as equities, fixed income, commodities and multi-asset classes. 

## Instructions and Install Packages

The Jupyter nodebook must be run under python 3.6.  Type the below commands in the Terminal to  to create and activate a conda environment.

```
conda create -n py36 python=3.6 anaconda
activate py36 #if on Windows
source activate py36 #if on Linux or MacOS
```

After that, run the main notebook `project_3.ipynb` using the above local environment.

### Main Files: Jupyter Structure

```
├── Part 1: calcuate the tracking error using divident yield against market cap weighted index
    ├── Simulate index weights
    ├── Simulate dividend weights
    ├── Generate close returns
    ├── Generate weighted returns
    └── Compute the tracking error
└── Part 2: optimize portfolio by minimize the variance and distance from weights of the market cap weighted index
    ├── Compute the optimial weights using cvxpy
    └── Rebalance Portfolio Over Time

```

### Authors

Jinjin Liang authored the main functions in `project_3.ipynb`, and this README. All other project files were created by [Udacity](https://www.udacity.com/).

