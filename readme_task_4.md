# Task 4: Classification with Logistic Regression (AI & ML Internship)

##  Objective
Build a binary classification model using Logistic Regression and evaluate its performance using multiple metrics.

##  Dataset
- **Breast Cancer Wisconsin Dataset** ([Kaggle link](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data))
- Target variable: `diagnosis` (Malignant = 1, Benign = 0)

##  Steps Performed
1. **Imported and explored dataset**
   - Used Pandas to load data and checked dataset shape, missing values, and data types.

2. **Preprocessed dataset**
   - Dropped irrelevant columns (`id`, `Unnamed: 32`).
   - Converted target variable `diagnosis` into numeric values (M → 1, B → 0).

3. **Split dataset into train and test sets**
   - Applied `train_test_split` (80% training, 20% testing).

4. **Standardized features**
   - Used `StandardScaler` to scale features for better model convergence.

5. **Trained Logistic Regression model**
   - Fitted the model on training data and made predictions on test data.

6. **Evaluated model performance**
   - Confusion Matrix (True Positives, False Positives, etc.).
   - Precision, Recall, F1-score from classification report.
   - ROC Curve and AUC score.

7. **Tuned decision threshold**
   - Experimented with custom probability thresholds to balance Precision and Recall.

8. **Visualized Sigmoid Function**
   - Plotted the sigmoid curve to understand logistic regression decision boundaries.

##  Evaluation Metrics
- **Confusion Matrix:** Visualized classification results.
- **Precision & Recall:** Measured accuracy of positive predictions.
- **ROC-AUC:** Evaluated model discrimination ability.
- **Threshold tuning:** Adjusted sensitivity of predictions.

##  Tools Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

##  Deliverables
- Jupyter Notebook: `task4.ipynb`
- README documentation (this file)



