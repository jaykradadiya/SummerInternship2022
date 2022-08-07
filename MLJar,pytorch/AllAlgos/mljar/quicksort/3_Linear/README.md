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

4.0 seconds

### Metric details:
| Metric   |    Score |
|:---------|---------:|
| MAE      | 0.304665 |
| MSE      | 0.215156 |
| RMSE     | 0.463849 |
| R2       | 0.710746 |
| MAPE     | 1.00966  |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature    |   Learner_1 |
|:-----------|------------:|
| feature_12 |   0.787992  |
| feature_6  |   0.778799  |
| feature_1  |   0.0688027 |
| feature_9  |   0.0554569 |
| feature_4  |  -0.0133161 |
| feature_7  |  -0.0133161 |
| intercept  |  -0.0190886 |
| feature_8  |  -0.0411548 |
| feature_10 |  -0.140356  |
| feature_5  |  -0.216825  |
| feature_13 |  -0.3024    |
| feature_11 |  -0.316251  |


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
