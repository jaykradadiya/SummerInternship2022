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

5.3 seconds

### Metric details:
| Metric   |    Score |
|:---------|---------:|
| MAE      | 0.481189 |
| MSE      | 0.400043 |
| RMSE     | 0.63249  |
| R2       | 0.595341 |
| MAPE     | 3.55014  |



## Learning curves
![Learning curves](learning_curves.png)

## Decision Tree 

### Tree #1
![Tree 1](learner_fold_0_tree.svg)

### Rules

if (feature_5 > -0.558) and (feature_4 > -0.511) and (feature_7 <= 0.372) then response: -0.707 | based on 500 samples

if (feature_5 > -0.558) and (feature_4 > -0.511) and (feature_7 > 0.372) then response: 0.243 | based on 249 samples

if (feature_5 <= -0.558) and (feature_1 > -1.065) and (feature_13 <= 0.424) then response: 0.669 | based on 186 samples

if (feature_5 > -0.558) and (feature_4 <= -0.511) and (feature_14 <= 0.192) then response: 1.061 | based on 89 samples

if (feature_5 > -0.558) and (feature_4 <= -0.511) and (feature_14 > 0.192) then response: -0.097 | based on 79 samples

if (feature_5 <= -0.558) and (feature_1 > -1.065) and (feature_13 > 0.424) then response: -0.386 | based on 49 samples

if (feature_5 <= -0.558) and (feature_1 <= -1.065) and (feature_1 > -1.633) then response: 2.321 | based on 28 samples

if (feature_5 <= -0.558) and (feature_1 <= -1.065) and (feature_1 <= -1.633) then response: 3.985 | based on 11 samples





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
