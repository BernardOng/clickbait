# Baseline Model + StratifiedKFold - FIXED ROC
**Model Performance Score Report**

### K-Fold Classification Report
| K | Accuracy | Precision | Recall | F-Measure | AUC | Kappa |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | 0.744863013699 | 0.511111111111 | 0.102449888641 | 0.170686456401 | 0.534340830737 | 0.0930668853097 |
| 2 | 0.725299828669 | 0.387323943662 | 0.122494432071 | 0.186125211506 | 0.527837077787 | 0.0717427603119 |
| 3 | 0.736721873215 | 0.445454545455 | 0.109131403118 | 0.175313059034 | 0.531140202327 | 0.0827450004488 |
| 4 | 0.743575099943 | 0.5 | 0.15144766147 | 0.232478632479 | 0.54961015946 | 0.128582465 |
| 5 | 0.75271273558 | 0.544943820225 | 0.216035634744 | 0.309409888357 | 0.576911826589 | 0.191730994539 |
| 6 | 0.738285714286 | 0.446808510638 | 0.09375 | 0.154981549815 | 0.526905721966 | 0.0726342048142 |
| 7 | 0.743428571429 | 0.497267759563 | 0.203125 | 0.288431061807 | 0.566232238863 | 0.164346440749 |
| 8 | 0.749142857143 | 0.519313304721 | 0.270089285714 | 0.355359765051 | 0.592033890169 | 0.218449574865 |
| 9 | 0.738285714286 | 0.46835443038 | 0.165178571429 | 0.244224422442 | 0.550331221198 | 0.127791827905 |
| 10 | 0.736 | 0.422222222222 | 0.0848214285714 | 0.14126394052 | 0.522441436252 | 0.0608228980322 |

### Average Confusion Matrix
| | Pred POS | Pred NEG |
| --- | --- | --- |
| **True POS** | 68.1 | 380.4 |
| **True NEG** | 73.3 | 1228.8 |

### Average Model Performance Metrics
| ACC | PRE | REC | F1 | AUC | KAPP |
| --- | --- | --- | --- | --- | --- |
| 0.740831540825 | 0.474279964798 | 0.151852330576 | 0.225827398741 | 0.547778460535 | 0.121191305197 |

### AUC/ROC Plot
![ROC Plot](baseline_model_+_stratifiedkfold_-_fixed_roc_auc-plot.png)