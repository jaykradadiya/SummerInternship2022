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

4.8 seconds

### Metric details:
| Metric   |    Score |
|:---------|---------:|
| MAE      | 0.381788 |
| MSE      | 0.273196 |
| RMSE     | 0.522681 |
| R2       | 0.664435 |
| MAPE     | 5.22992  |



## Learning curves
![Learning curves](learning_curves.png)

## Decision Tree 

### Tree #1
![Tree 1](learner_fold_0_tree.svg)

### Rules

if (feature_1 > -1.254) and (feature_10 <= 0.386) and (feature_4 > -0.511) then response: 0.203 | based on 666 samples

if (feature_1 > -1.254) and (feature_10 > 0.386) and (feature_14 > -1.123) then response: -0.473 | based on 370 samples

if (feature_1 > -1.254) and (feature_10 <= 0.386) and (feature_4 <= -0.511) then response: -0.64 | based on 88 samples

if (feature_1 <= -1.254) and (feature_6 <= -0.446) and (feature_1 > -1.633) then response: 3.231 | based on 24 samples

if (feature_1 > -1.254) and (feature_10 > 0.386) and (feature_14 <= -1.123) then response: -1.4 | based on 18 samples

if (feature_1 <= -1.254) and (feature_6 <= -0.446) and (feature_1 <= -1.633) then response: 4.858 | based on 11 samples

if (feature_1 <= -1.254) and (feature_6 > -0.446) and (feature_1 > -1.444) then response: 0.258 | based on 8 samples

if (feature_1 <= -1.254) and (feature_6 > -0.446) and (feature_1 <= -1.444) then response: 0.522 | based on 6 samples





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
