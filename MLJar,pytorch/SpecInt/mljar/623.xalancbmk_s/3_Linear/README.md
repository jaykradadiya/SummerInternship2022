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
| MAE      | 0.431954 |
| MSE      | 0.515327 |
| RMSE     | 0.717863 |
| R2       | 0.497677 |
| MAPE     | 1.43954  |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature    |    Learner_1 |
|:-----------|-------------:|
| feature_13 |  1.174e+13   |
| feature_11 |  1.05302e+13 |
| feature_7  |  6.9798e+11  |
| feature_12 |  2.07869e+11 |
| feature_5  |  0.331653    |
| feature_4  |  0.109859    |
| feature_3  |  0.0786028   |
| intercept  | -0.00590097  |
| feature_14 | -0.0652967   |
| feature_6  | -0.342807    |
| feature_1  | -0.457479    |
| feature_9  | -1.0221e+12  |
| feature_8  | -1.04014e+12 |
| feature_10 | -3.39765e+12 |


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
