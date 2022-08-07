# Summary of 3_Linear

[<< Go back](../README.md)


## Linear Regression (Linear)
- **n_jobs**: -1
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True

## Optimized metric
rmse

## Training time

3.3 seconds

### Metric details:
| Metric   |    Score |
|:---------|---------:|
| MAE      | 0.385729 |
| MSE      | 0.612019 |
| RMSE     | 0.782317 |
| R2       | 0.608279 |
| MAPE     | 0.388159 |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature    |   Learner_1 |
|:-----------|------------:|
| feature_10 |   0.84307   |
| feature_9  |   0.184072  |
| intercept  |   0.0536651 |
| feature_7  |   0.0159434 |
| feature_8  |  -0.0159434 |
| feature_6  |  -0.0821365 |
| feature_12 |  -0.41646   |
| feature_11 |  -0.773914  |
| feature_1  |  -0.985201  |
| feature_5  |  -1.45747   |


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
