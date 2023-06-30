# Apartment Building Design Project

## Introduction
This project involves designing a new apartment building for the Stargrove Development Corporation in Philadelphia. The goal is to determine the optimal allocation of regular and luxury apartments across the building's 15 floors to maximize profit. The project takes into account the projected demand for each apartment type, the selling prices, and salvage profits for unsold apartments.

## Overview
The Stargrove Development Corporation plans to construct an apartment building with 15 floors. The lower floors will accommodate regular apartments, while the higher floors will house luxury apartments. The number of regular and luxury apartments on each floor needs to be determined based on market demand and profitability.

## Problems
1) Allocation of floors between regular and luxury apartments.
2) Estimating the expected profit and risk associated with the chosen allocation.
3) Comparing different allocation strategies to identify the most profitable and acceptable risk level.

## Approach to Problem
To solve the problem, the following approach is taken:

1) Calculate the number of regular and luxury apartments sold based on the demand and availability.
2) Determine the number of unsold apartments that will be salvaged.
3) Calculate the profit by multiplying the number of sold and salvaged apartments with their respective selling prices.
4) Simulate the profit calculation by generating random demand values for regular and luxury apartments.
5) Repeat the simulation multiple times to obtain a sample distribution of profits.
6) Analyze the simulation output to estimate the expected profit and assess the risk associated with the allocation plan.

## Analysis
The analysis involves running simulations to generate random demand values for regular and luxury apartments. By repeating the simulation multiple times, a sample distribution of profits can be obtained. Excel can be used to run the simulations and analyze the results. The sample mean provides an estimate of the expected profit, while confidence intervals offer insights into the range of likely values.

## Results and Inference
Based on the simulation results with a sample size of 1000 runs:

- The expected profit for the allocation of 12 regular floors and 3 luxury floors is estimated to be between $51,727,814 and $52,534,408 (95% confidence interval).
- The risk associated with this allocation, measured by the standard deviation of profits, falls between 0.133 and 0.179.

It is concluded that the allocation of 12 regular floors and 3 luxury floors is expected to yield higher profit compared to other allocations tested. However, further analysis is required to assess risk levels accurately.

## Conclusion
The apartment building design project aims to optimize the allocation of regular and luxury apartments to maximize profit. Through simulation and analysis, the project provides estimates of expected profit and risk measures associated with different allocation strategies. These insights enable decision-makers to select the most profitable and acceptable risk level based on their priorities and preferences.

For detailed implementation, please refer to the project files.

Note: The analysis and results mentioned above are based on simulated data and should be interpreted as estimates.
