# Decision-Focused Learning Enhanced by Automated Feature Engineering for Energy Storage Optimisation

Welcome to the repository for the **Decision-Focused Learning Enhanced by Automated Feature Engineering for Energy Storage Optimisation** paper.

- The paper is currently under review. The code and data will be made available soon.
- This repository hosts the **Supplementary Materials** for the paper.



## Objectives
- **Minimise energy costs while meeting demand**: Optimise battery charging schedules to take advantage of lower electricity prices.  
- **Enhance DFL with automated feature engineering**: We used [**AutoEnergy**](https://www.sciencedirect.com/science/article/pii/S0950705125013413), an automated feature engineering algorithm, to enhance emerging DFL methods while minimising reliance on domain expertise, thereby streamlining the development of full predict-and-optimise pipelines for energy storage optimisation problems.




## Introduction

Traditional machine learning approaches often separate prediction and decision-making processes, which can lead to suboptimal outcomes due to error propagation. **DFL** integrates prediction and optimisation into a single end-to-end learning framework, directly aligning model predictions with decision-making objectives.

In this study, we focus on:

- **Multiple Unknowns**: Predicting future energy prices and household energy demand for the 24-hour horizon.
  - **Q**: **What will energy costs be for the next 24 hours? What levels of demand can be expected?**

- **Decision-Making**: Determining optimal charging times and levels for batteries within the 24-hour forecasting period.
  - **Q**: **When should Cha/Disrging occur during this period? And by how much?**




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
  

## Citation

```bibtex
@article{xx,
  title={Decision-Focused Learning Enhanced by Automated Feature Engineering for Energy Storage Optimisation},
  author={...},
  journal={Under Review},
  year={2025}
}

