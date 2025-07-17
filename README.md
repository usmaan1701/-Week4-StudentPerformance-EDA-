1. The HR attrition dataset is loaded using `pandas.read_csv()` for analysis.
2. Initial exploration is done using `.info()`, `.describe()`, and `.value_counts()`.
3. Irrelevant columns like `EmployeeCount` and `Over18` are dropped for cleaner data.
4. Categorical features are encoded using `LabelEncoder` for model compatibility.
5. Feature scaling is performed using `StandardScaler` to normalize numerical data.
6. SMOTE is applied to handle class imbalance between attrition and non-attrition cases.
7. Data visualization includes countplots and heatmaps for exploratory analysis.
8. Three classification models — Logistic Regression, Random Forest, and XGBoost — are trained.
9. Models are evaluated using confusion matrix and classification report metrics.
10. Feature importance is visualized to identify key factors influencing attrition.
