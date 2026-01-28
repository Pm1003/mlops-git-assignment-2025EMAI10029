## Manual Experiment Tracking Table

| Experiment ID | Model Type    | Hyperparameters      | Preprocessing Steps        | Feature Selection  | Train/Test Split | Precision | AUC Score |
| ------------- | ------------- | -------------------- | -------------------------- | ------------------ | ---------------- | --------- | --------- |
| EXP-01        | Decision Tree | max_depth=5, gini    | Standardization + Encoding | All 15 features    | 80/20            | 0.7297    | 0.8616    |
| EXP-02        | Decision Tree | max_depth=3, entropy | Standardization            | Numeric 5 features | 80/20            | 0.7297    | 0.8974    |
| EXP-03        | k-NN          | k=7                  | Standardization + Encoding | All 15 features    | 70/30            | 0.7069    | 0.8564    |
| EXP-04        | Naive Bayes   | Default              | Standardization            | Numeric 5 features | 75/25            | 0.5306    | 0.7744    |
