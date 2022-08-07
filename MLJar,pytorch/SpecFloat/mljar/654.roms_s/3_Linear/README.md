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

4.4 seconds

### Metric details:
| Metric   |    Score |
|:---------|---------:|
| MAE      | 0.216602 |
| MSE      | 0.108433 |
| RMSE     | 0.329292 |
| R2       | 0.892315 |
| MAPE     | 0.953843 |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature    |    Learner_1 |
|:-----------|-------------:|
| feature_13 |  8.93644e+12 |
| feature_11 |  8.24689e+12 |
| feature_7  |  1.21745e+12 |
| feature_12 |  2.16445e+11 |
| intercept  |  0.0167362   |
| feature_1  |  0.00857002  |
| feature_3  | -0.0449632   |
| feature_14 | -0.0742048   |
| feature_6  | -0.0922836   |
| feature_5  | -0.518907    |
| feature_4  | -0.765801    |
| feature_10 | -3.32862e+11 |
| feature_8  | -3.37896e+11 |
| feature_9  | -2.12214e+12 |


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
