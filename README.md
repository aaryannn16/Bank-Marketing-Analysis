Improvement Step – SMOTE

To address class imbalance, I applied SMOTE (Synthetic Minority Oversampling Technique) during training. This rebalanced the training data and helped the model improve recall for the minority class (subscribers).

- Recall for class 1 improved from 41% to 43%
- F1-score slightly increased from 0.51 to 0.52
- ROC AUC remained stable 0.93 to 0.92

Although the accuracy slightly decreased from 91% to 90%, the model now performs better at detecting actual subscribers, which is crucial in marketing scenarios where missing a potential lead is more costly than a false positive.
