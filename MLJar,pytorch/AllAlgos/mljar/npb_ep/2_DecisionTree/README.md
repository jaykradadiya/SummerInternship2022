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

10.1 seconds

### Metric details:
| Metric   |    Score |
|:---------|---------:|
| MAE      | 0.528378 |
| MSE      | 0.662316 |
| RMSE     | 0.813828 |
| R2       | 0.659828 |
| MAPE     | 1.45905  |



## Learning curves
![Learning curves](learning_curves.png)

## Decision Tree 

### Tree #1
![Tree 1](learner_fold_0_tree.svg)

### Rules

if (feature_12 > -0.79) and (feature_12 <= -0.137) and (feature_9 <= 1.438) then response: -0.033 | based on 19 samples

if (feature_12 > -0.79) and (feature_12 > -0.137) and (feature_6 <= 0.968) then response: -0.812 | based on 17 samples

if (feature_12 > -0.79) and (feature_12 > -0.137) and (feature_6 > 0.968) then response: -0.46 | based on 10 samples

if (feature_12 <= -0.79) and (feature_12 > -1.051) and (feature_9 <= 0.847) then response: 0.969 | based on 7 samples

if (feature_12 > -0.79) and (feature_12 <= -0.137) and (feature_9 > 1.438) then response: -0.641 | based on 4 samples

if (feature_12 <= -0.79) and (feature_12 > -1.051) and (feature_9 > 0.847) then response: -0.109 | based on 3 samples

if (feature_12 <= -0.79) and (feature_12 <= -1.051) and (feature_9 <= 1.438) then response: 2.17 | based on 3 samples

if (feature_12 <= -0.79) and (feature_12 <= -1.051) and (feature_9 > 1.438) then response: 1.14 | based on 1 samples





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
