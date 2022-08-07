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
| MAE      | 0.194468 |
| MSE      | 0.133006 |
| RMSE     | 0.3647   |
| R2       | 0.666866 |
| MAPE     | 1.04219  |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature    |    Learner_1 |
|:-----------|-------------:|
| feature_13 |  8.53688e+12 |
| feature_11 |  7.87817e+12 |
| feature_7  |  1.16302e+12 |
| feature_12 |  2.06767e+11 |
| intercept  |  0.0146235   |
| feature_1  |  0.00570907  |
| feature_3  | -0.0115584   |
| feature_14 | -0.0540714   |
| feature_5  | -0.245859    |
| feature_6  | -0.328705    |
| feature_4  | -0.422762    |
| feature_10 | -3.1798e+11  |
| feature_8  | -3.22789e+11 |
| feature_9  | -2.02725e+12 |


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
