# Decision-Focused Learning for Batteries Energy Efficiency

Welcome to the repository for the **Decision-Focused Learning Enhanced by Automated Feature Engineering for Energy Storage Optimisation** paper. This research explores the application of DFL vs. PTO to optimise battery charging strategies in residential settings, aiming to reduce energy costs and improve efficiency.

This repository also hosts the **Supplementary Material** for the paper.




## Introduction

Traditional machine learning approaches often separate prediction and decision-making processes, which can lead to suboptimal outcomes due to error propagation. **DFL** integrates prediction and optimisation into a single end-to-end learning framework, directly aligning model predictions with decision-making objectives.

In this study, we focus on:

- **Multiple Unknowns**: Predicting future energy prices and household energy demand for the 24-hour horizon.
  - **Q**: **What will energy costs be for the next 24 hours? What levels of demand can be expected?**

- **Decision-Making**: Determining optimal charging times and levels for batteries within the 24-hour forecasting period.
  - **Q**: **When should Cha/Disrging occur during this period? And by how much?**


## Objectives
- **Minimise Energy Costs while meeting the demand**: Optimise battery charging schedules to take advantage of lower electricity prices.


## Dataset
The dataset includes:

- **Batteries and Household Energy Demand Data** (sourced from Intelligent Plant: https://www.intelligentplant.com)
- **Energy Prices** (sourced Octopus Energy API https://developer.octopus.energy/rest/guides/api-basics).

## Repository Structure

.....

##

### Prerequisites

- Python 3.11.5
- Install dependencies using:

  ```bash
  pip install -r requirements.txt
  



 **Note:** The paper is currently under review. The full dataset and code will be made available soon.

## Citation

@article{xx,
  title={Decision-Focused Learning Enhanced by Automated Feature Engineering for Energy Storage Optimisation},
  author={...},
  journal={Under Review},
  year={2025}
}
