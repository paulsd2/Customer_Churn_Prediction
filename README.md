#Customer Churn Prediction
###This project focuses on predicting customer churn using machine learning techniques.
###The goal is to identify customers who are likely to stop using a service so that retention strategies can
be applied.
###Project Structure
- data/: Raw & processed datasets
- notebooks/: Jupyter notebooks with EDA & models
- models/: Saved ML models
- results/: Output plots, metrics, and predictions
###Workflow
1. Exploratory Data Analysis (EDA)
- Checked class balance (churn vs non-churn).
- Visualized demographics and usage patterns.
- Found key churn drivers (contract type, monthly charges, tenure).
2. Data Preprocessing
- Missing value handling
- Encoding categorical features
- Feature scaling
3. Modeling
- Logistic Regression, Random Forest, XGBoost
- Compared accuracy, precision, recall, F1, AUC
4. Evaluation
- Best models: Random Forest / XGBoost
- ROC-AUC ~0.85-0.90
5. Prediction
- Final model outputs probability of churn per customer.
###Results
- Accuracy: ~85%
- Recall (Churn): ~80%
- ROC-AUC: ~0.88
###Key insights:
- Month-to-month contracts & higher charges → higher churn
- Longer tenure → lower churn
###Tech Stack
- Python (Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn)
- Jupyter Notebook
###Conclusion
This project shows how ML helps predict churn and allows proactive retention measures.
