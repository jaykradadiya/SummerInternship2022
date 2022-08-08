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

3.0 seconds

### Metric details:
| Metric   |    Score |
|:---------|---------:|
| MAE      | 0.343527 |
| MSE      | 0.264574 |
| RMSE     | 0.514367 |
| R2       | 0.829745 |
| MAPE     | 0.291006 |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature    |   Learner_1 |
|:-----------|------------:|
| feature_10 |   0.607543  |
| feature_8  |   0.3505    |
| intercept  |  -0.0257246 |
| feature_11 |  -0.0546187 |
| feature_1  |  -0.067834  |
| feature_12 |  -0.336178  |
| feature_7  |  -0.3505    |
| feature_5  |  -0.566921  |
| feature_9  |  -0.698521  |
| feature_6  |  -0.711677  |


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
