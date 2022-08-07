# Summary of 2_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: mse
- **max_depth**: 3
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True

## Optimized metric
rmse

## Training time

11.3 seconds

### Metric details:
| Metric   |    Score |
|:---------|---------:|
| MAE      | 0.436984 |
| MSE      | 0.489668 |
| RMSE     | 0.699763 |
| R2       | 0.517625 |
| MAPE     | 7.38361  |



## Learning curves
![Learning curves](learning_curves.png)

## Decision Tree 

### Tree #1
![Tree 1](learner_fold_0_tree.svg)

### Rules

if (feature_1 > -1.254) and (feature_5 <= 0.372) and (feature_7 <= 0.372) then response: -0.36 | based on 598 samples

if (feature_1 > -1.254) and (feature_5 <= 0.372) and (feature_7 > 0.372) then response: 0.089 | based on 338 samples

if (feature_1 > -1.254) and (feature_5 > 0.372) and (feature_14 > -0.059) then response: -0.214 | based on 121 samples

if (feature_1 > -1.254) and (feature_5 > 0.372) and (feature_14 <= -0.059) then response: 1.024 | based on 85 samples

if (feature_1 <= -1.254) and (feature_6 <= -0.446) and (feature_1 > -1.633) then response: 3.079 | based on 24 samples

if (feature_1 <= -1.254) and (feature_6 <= -0.446) and (feature_1 <= -1.633) then response: 5.171 | based on 11 samples

if (feature_1 <= -1.254) and (feature_6 > -0.446) and (feature_14 <= -0.184) then response: 0.045 | based on 8 samples

if (feature_1 <= -1.254) and (feature_6 > -0.446) and (feature_14 > -0.184) then response: -0.127 | based on 6 samples





## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## True vs Predicted

![True vs Predicted](true_vs_predicted.png)


## Predicted vs Residuals

![Predicted vs Residuals](predicted_vs_residuals.png)



## SHAP Importance
![SHAP Importance](shap_importance.png)

## SHAP Dependence plots

### Dependence (Fold 1)
![SHAP Dependence from Fold 1](learner_fold_0_shap_dependence.png)

## SHAP Decision plots

### Top-10 Worst decisions (Fold 1)
![SHAP worst decisions from fold 1](learner_fold_0_shap_worst_decisions.png)
### Top-10 Best decisions (Fold 1)
![SHAP best decisions from fold 1](learner_fold_0_shap_best_decisions.png)

[<< Go back](../README.md)
