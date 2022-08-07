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

4.5 seconds

### Metric details:
| Metric   |    Score |
|:---------|---------:|
| MAE      | 0.244359 |
| MSE      | 0.199213 |
| RMSE     | 0.446332 |
| R2       | 0.50105  |
| MAPE     | 2.44226  |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature    |    Learner_1 |
|:-----------|-------------:|
| feature_13 |  1.20037e+13 |
| feature_11 |  1.07667e+13 |
| feature_7  |  7.13657e+11 |
| feature_12 |  2.12538e+11 |
| feature_5  |  0.432124    |
| feature_4  |  0.134877    |
| feature_3  |  0.0621445   |
| intercept  | -0.0080674   |
| feature_14 | -0.059491    |
| feature_6  | -0.426037    |
| feature_1  | -0.475722    |
| feature_9  | -1.04505e+12 |
| feature_8  | -1.0635e+12  |
| feature_10 | -3.47396e+12 |


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
