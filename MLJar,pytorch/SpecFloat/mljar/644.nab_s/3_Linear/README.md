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

4.1 seconds

### Metric details:
| Metric   |    Score |
|:---------|---------:|
| MAE      | 0.279748 |
| MSE      | 0.319264 |
| RMSE     | 0.565034 |
| R2       | 0.620556 |
| MAPE     | 0.762798 |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature    |    Learner_1 |
|:-----------|-------------:|
| feature_13 |  7.71007e+12 |
| feature_11 |  7.11515e+12 |
| feature_7  |  1.05038e+12 |
| feature_12 |  1.86742e+11 |
| intercept  |  0.0212577   |
| feature_3  | -0.018439    |
| feature_14 | -0.0271178   |
| feature_1  | -0.0599848   |
| feature_5  | -0.218017    |
| feature_6  | -0.430964    |
| feature_4  | -0.473746    |
| feature_10 | -2.87183e+11 |
| feature_8  | -2.91526e+11 |
| feature_9  | -1.83091e+12 |


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
