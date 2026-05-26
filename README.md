# comment-category-prediction
Supervised ML models for comment classification
Overview: Kaggle competition, supervised classification task.
Models tried: Logistic Regression, Random Forest, LightGBM.
Outcome: LightGBM chosen for best score.
Results: Leaderboard score: 0.81

## Dataset
This dataset was provided by my university through a private Kaggle competition.  
Due to access restrictions, the raw files (`train.csv`, `test.csv`, `sample_submission.csv`) are not included in this   
- train.csv: training data with labels  
- test.csv: test data without labels  
- sample_submission.csv: submission format 

## Workflow
The entire pipeline is implemented in a single Jupyter Notebook:
1. Loading datasets
2. Exploratory Data Analysis (EDA)
3. Visualising data
4. Imputing missing values
5. Feature engineering
6. Encoding categorical features
7. Scaling numeric features
8. Text cleaning using regex
9. Text feature extraction
10. Dimensionality reduction
11. Model training (LR, RF, LightGBM)
12. Model performance evaluation
13. Final prediction
14. Submission file generation
