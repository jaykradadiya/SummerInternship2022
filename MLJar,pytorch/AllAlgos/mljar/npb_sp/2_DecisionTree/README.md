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

4.4 seconds

### Metric details:
| Metric   |    Score |
|:---------|---------:|
| MAE      | 0.276607 |
| MSE      | 0.196818 |
| RMSE     | 0.443642 |
| R2       | 0.873346 |
| MAPE     | 0.255148 |



## Learning curves
![Learning curves](learning_curves.png)

## Decision Tree 

### Tree #1
![Tree 1](learner_fold_0_tree.svg)

### Rules

if (feature_5 > -0.561) and (feature_12 > -0.826) and (feature_6 <= 0.968) then response: -0.56 | based on 25 samples

if (feature_5 <= -0.561) and (feature_9 > -1.225) and (feature_12 <= -0.336) then response: 0.782 | based on 17 samples

if (feature_5 > -0.561) and (feature_12 > -0.826) and (feature_6 > 0.968) then response: -1.18 | based on 11 samples

if (feature_5 > -0.561) and (feature_12 <= -0.826) and (feature_9 > 1.142) then response: -0.265 | based on 3 samples

if (feature_5 > -0.561) and (feature_12 <= -0.826) and (feature_9 <= 1.142) then response: 1.179 | based on 3 samples

if (feature_5 <= -0.561) and (feature_9 > -1.225) and (feature_12 > -0.336) then response: 0.99 | based on 2 samples

if (feature_5 <= -0.561) and (feature_9 <= -1.225) and (feature_12 > -0.642) then response: 1.762 | based on 2 samples

if (feature_5 <= -0.561) and (feature_9 <= -1.225) and (feature_12 <= -0.642) then response: 1.219 | based on 1 samples





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
