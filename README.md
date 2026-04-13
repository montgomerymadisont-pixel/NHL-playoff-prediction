# NHL Playoff Prediction Model

## Overview
This project develops a machine learning model to predict NHL postseason outcomes using regular season performance metrics. The NHL is known for high playoff unpredictability, making it an ideal test case for classification modeling.

## Approach
- Built a multinomial logistic regression model to classify teams into:
  - Non-playoff
  - Playoff participant
  - Conference finalist
  - Stanley Cup winner
- Addressed class imbalance using custom weighting strategies
- Engineered features including:
  - Goal differential
  - Points percentage
  - Special teams efficiency
  - Possession metrics (Corsi, Fenwick)

## Results
- Achieved **94% accuracy** in predicting playoff teams from late-season data
- Outperformed typical benchmarks (~60–65%)
- Successfully identified high-performing teams based on statistical indicators

## Key Insights
- Traditional metrics alone are insufficient—feature interaction matters
- Class imbalance significantly impacts predictive performance
- Logistic regression provided strong interpretability and competitive accuracy

## Tools Used
- Python (Pandas, Scikit-learn, Seaborn)
- Google Colab

## Note
Code will be uploaded in a future update. This repository currently highlights methodology, results, and analysis.
