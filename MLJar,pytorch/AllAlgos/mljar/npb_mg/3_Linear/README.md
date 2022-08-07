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

3.4 seconds

### Metric details:
| Metric   |     Score |
|:---------|----------:|
| MAE      | 0.230371  |
| MSE      | 0.0770331 |
| RMSE     | 0.277548  |
| R2       | 0.937928  |
| MAPE     | 0.272481  |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature    |   Learner_1 |
|:-----------|------------:|
| feature_11 |   1.89142   |
| feature_5  |   1.36671   |
| feature_8  |   0.510669  |
| feature_1  |   0.303829  |
| intercept  |   0.0347258 |
| feature_12 |  -0.157986  |
| feature_7  |  -0.510669  |
| feature_9  |  -1.32654   |
| feature_6  |  -1.86081   |
| feature_10 |  -2.08487   |


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
