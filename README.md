# DataScience-final-
# La Liga Match Outcome Prediction

**Course:** Machine Learning & AI — Final Exam Project  
## Overview
Predicting whether a La Liga football match ends in a Home Win, Draw,
or Away Win using historical match statistics and team quality ratings.

## Data Sources
- **Source 1:** football-data.co.uk — match results, shots, cards (4 seasons)
- **Source 2:** FIFA Team Ratings via Kaggle (Hugo Mathien)

## Methods
- Multinomial Logistic Regression with L2 regularisation
- StandardScaler preprocessing pipeline
- Chronological train/test split (no data leakage)
- 5-fold stratified cross-validation + hyperparameter search

## Structure
The project is a single Jupyter notebook built incrementally across 10 commits.

## How to Run
1. Clone the repo
2. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn scipy`
3. Open `LaLiga_Match_Prediction.ipynb` and run all cells top to bottom

## References
See Section 11 of the notebook for all 8 references.
