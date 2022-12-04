# AutoML-examples
  - Describe the two dependent variables (outcomes) for experiment 1 and experiment 2 
    - Describe for each experiment: 
        - What was the best performing model (please interpret (a) log-loss or RMSE between models, and (b) AUC) 
        - How much better (? if any) did the model perform compared to baseline

Experiment 1: Binary 
Dependent V: Type of Admission 
Best model: Xgboost
Log-loss: 0.214198 (79.5% better than baseline)
Baseline: 1.047051 


Experiment 2: Continous 
Dependent V: Total charges 
Best model: Ensemble
RMSE: 4785.876276 (79.7% better than baseline)
Baseline: 23541.268908 
