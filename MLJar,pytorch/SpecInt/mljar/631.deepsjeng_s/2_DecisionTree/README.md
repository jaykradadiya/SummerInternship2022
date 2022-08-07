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

6.3 seconds

### Metric details:
| Metric   |    Score |
|:---------|---------:|
| MAE      | 0.318123 |
| MSE      | 0.160069 |
| RMSE     | 0.400086 |
| R2       | 0.733894 |
| MAPE     | 5.49858  |



## Learning curves
![Learning curves](learning_curves.png)

## Decision Tree 

### Tree #1
![Tree 1](learner_fold_0_tree.svg)

### Rules

if (feature_1 > -1.245) and (feature_1 <= 0.205) and (feature_7 <= 0.373) then response: -0.057 | based on 510 samples

if (feature_1 > -1.245) and (feature_1 > 0.205) and (feature_14 > -1.146) then response: -0.244 | based on 326 samples

if (feature_1 > -1.245) and (feature_1 <= 0.205) and (feature_7 > 0.373) then response: 0.395 | based on 223 samples

if (feature_1 > -1.245) and (feature_1 > 0.205) and (feature_14 <= -1.146) then response: -0.778 | based on 85 samples

if (feature_1 <= -1.245) and (feature_6 <= -0.42) and (feature_1 > -1.619) then response: 2.584 | based on 21 samples

if (feature_1 <= -1.245) and (feature_6 > -0.42) and (feature_13 > -1.815) then response: 0.134 | based on 14 samples

if (feature_1 <= -1.245) and (feature_6 <= -0.42) and (feature_1 <= -1.619) then response: 4.347 | based on 11 samples

if (feature_1 <= -1.245) and (feature_6 > -0.42) and (feature_13 <= -1.815) then response: 0.267 | based on 1 samples





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
