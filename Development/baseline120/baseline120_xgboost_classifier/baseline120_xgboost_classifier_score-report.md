# Baseline120 XGBoost Classifier
**Model Performance Score Report**

### K-Fold Classification Report
| K | Accuracy | Precision | Recall | F-Measure | AUC | Kappa |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | 1.0 | 1.0 | 1.0 | 1.0 | 1.0 | 1.0 |
| 2 | 1.0 | 1.0 | 1.0 | 1.0 | 1.0 | 1.0 |
| 3 | 1.0 | 1.0 | 1.0 | 1.0 | 1.0 | 1.0 |
| 4 | 0.999428897773 | 1.0 | 0.997772828508 | 0.998885172798 | 0.998886414254 | 0.99850129628 |
| 5 | 0.999428897773 | 1.0 | 0.997772828508 | 0.998885172798 | 0.998886414254 | 0.99850129628 |
| 6 | 1.0 | 1.0 | 1.0 | 1.0 | 1.0 | 1.0 |
| 7 | 1.0 | 1.0 | 1.0 | 1.0 | 1.0 | 1.0 |
| 8 | 0.999428571429 | 1.0 | 0.997767857143 | 0.998882681564 | 0.998883928571 | 0.998498805049 |
| 9 | 0.999428571429 | 0.997772828508 | 1.0 | 0.998885172798 | 0.999615975422 | 0.998501001331 |
| 10 | 1.0 | 1.0 | 1.0 | 1.0 | 1.0 | 1.0 |

### Average Confusion Matrix
| | Pred POS | Pred NEG |
| --- | --- | --- |
| **True POS** | 448.2 | 0.3 |
| **True NEG** | 0.1 | 1302.0 |

### Average Model Performance Metrics
| ACC | PRE | REC | F1 | AUC | KAPP |
| --- | --- | --- | --- | --- | --- |
| 0.99977149384 | 0.999777282851 | 0.999331351416 | 0.999553819996 | 0.99962727325 | 0.999400239894 |

### AUC/ROC Plot
![ROC Plot](baseline120_xgboost_classifier_auc-plot.png)
