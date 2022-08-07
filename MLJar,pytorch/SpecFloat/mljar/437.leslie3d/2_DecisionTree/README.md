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

7.3 seconds

### Metric details:
| Metric   |    Score |
|:---------|---------:|
| MAE      | 0.32376  |
| MSE      | 0.214292 |
| RMSE     | 0.462916 |
| R2       | 0.776658 |
| MAPE     | 0.621774 |



## Learning curves
![Learning curves](learning_curves.png)

## Decision Tree 

### Tree #1
![Tree 1](learner_fold_0_tree.svg)

### Rules

if (feature_5 > -1.063) and (feature_7 <= -0.246) and (feature_1 <= 0.975) then response: 0.241 | based on 392 samples

if (feature_5 > -1.063) and (feature_7 > -0.246) and (feature_3 <= 0.181) then response: -0.842 | based on 373 samples

if (feature_5 > -1.063) and (feature_7 <= -0.246) and (feature_1 > 0.975) then response: -0.331 | based on 98 samples

if (feature_5 <= -1.063) and (feature_1 > -0.397) and (feature_4 > -1.698) then response: 1.237 | based on 83 samples

if (feature_5 <= -1.063) and (feature_1 <= -0.397) and (feature_1 > -1.312) then response: 2.422 | based on 21 samples

if (feature_5 <= -1.063) and (feature_1 <= -0.397) and (feature_1 <= -1.312) then response: 3.704 | based on 16 samples

if (feature_5 > -1.063) and (feature_7 > -0.246) and (feature_3 > 0.181) then response: 1.01 | based on 14 samples

if (feature_5 <= -1.063) and (feature_1 > -0.397) and (feature_4 <= -1.698) then response: 2.26 | based on 11 samples





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
