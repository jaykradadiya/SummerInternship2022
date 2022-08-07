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

4.6 seconds

### Metric details:
| Metric   |     Score |
|:---------|----------:|
| MAE      | 0.182882  |
| MSE      | 0.0969693 |
| RMSE     | 0.311399  |
| R2       | 0.921864  |
| MAPE     | 0.242583  |



## Learning curves
![Learning curves](learning_curves.png)

## Decision Tree 

### Tree #1
![Tree 1](learner_fold_0_tree.svg)

### Rules

if (feature_5 > -0.561) and (feature_11 <= 1.013) and (feature_12 > -1.025) then response: -0.394 | based on 27 samples

if (feature_5 <= -0.561) and (feature_9 > -1.225) and (feature_5 > -1.214) then response: 0.772 | based on 14 samples

if (feature_5 > -0.561) and (feature_11 > 1.013) and (feature_12 > -0.77) then response: -1.326 | based on 11 samples

if (feature_5 <= -0.561) and (feature_9 > -1.225) and (feature_5 <= -1.214) then response: 1.245 | based on 5 samples

if (feature_5 > -0.561) and (feature_11 > 1.013) and (feature_12 <= -0.77) then response: -0.643 | based on 2 samples

if (feature_5 > -0.561) and (feature_11 <= 1.013) and (feature_12 <= -1.025) then response: 0.405 | based on 2 samples

if (feature_5 <= -0.561) and (feature_9 <= -1.225) and (feature_12 <= -0.707) then response: 1.973 | based on 2 samples

if (feature_5 <= -0.561) and (feature_9 <= -1.225) and (feature_12 > -0.707) then response: 2.61 | based on 1 samples





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
