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

4.2 seconds

### Metric details:
| Metric   |    Score |
|:---------|---------:|
| MAE      | 0.180469 |
| MSE      | 0.07416  |
| RMSE     | 0.272323 |
| R2       | 0.924772 |
| MAPE     | 2.78509  |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature    |    Learner_1 |
|:-----------|-------------:|
| feature_13 |  1.16504e+13 |
| feature_11 |  1.07515e+13 |
| feature_7  |  1.58719e+12 |
| feature_12 |  2.82179e+11 |
| intercept  |  0.0145615   |
| feature_6  | -0.0172817   |
| feature_1  | -0.02759     |
| feature_3  | -0.0368699   |
| feature_14 | -0.147025    |
| feature_5  | -0.500497    |
| feature_4  | -0.874535    |
| feature_10 | -4.33953e+11 |
| feature_8  | -4.40516e+11 |
| feature_9  | -2.76663e+12 |


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
