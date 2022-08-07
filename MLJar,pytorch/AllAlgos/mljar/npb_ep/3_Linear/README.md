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

2.7 seconds

### Metric details:
| Metric   |    Score |
|:---------|---------:|
| MAE      | 0.55576  |
| MSE      | 1.16784  |
| RMSE     | 1.08066  |
| R2       | 0.399915 |
| MAPE     | 0.950883 |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature    |   Learner_1 |
|:-----------|------------:|
| feature_11 |   1.01414   |
| feature_8  |   0.161395  |
| intercept  |   0.0714694 |
| feature_1  |   0.0248885 |
| feature_5  |  -0.151731  |
| feature_7  |  -0.161395  |
| feature_6  |  -0.346447  |
| feature_9  |  -0.479122  |
| feature_10 |  -0.548011  |
| feature_12 |  -0.805267  |


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
