# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using classical machine learning techniques.  
The dataset is highly imbalanced, making accuracy an unreliable metric and requiring careful evaluation using more appropriate performance measures.

---

## Problem Statement

Credit card fraud detection is a real-world binary classification problem where fraudulent transactions represent a very small fraction of all transactions.  
The primary objective is to correctly identify fraudulent transactions while minimizing false negatives, as missing fraud cases can lead to significant financial losses.

---

## Dataset

- **Source:** Kaggle – Credit Card Fraud Detection  
    
- **Description:** The dataset contains anonymized credit card transaction features along with a binary target variable indicating fraud.
- **Class Distribution:**
  - `0` → Legitimate transaction  
  - `1` → Fraudulent transaction  

Due to file size constraints, the dataset is not included in this repository.

---

## Project Workflow

The project follows a structured and reproducible machine learning pipeline:

1. Exploratory Data Analysis (EDA)
2. Data preprocessing and feature scaling
3. Handling class imbalance
4. Model training using classical machine learning algorithms
5. Model evaluation using suitable performance metrics

---

## Models Used

- Logistic Regression  
- Tree-based / Boosting model  

These models were selected for their effectiveness on tabular data and their ability to perform well on highly imbalanced classification problems.

---

## Evaluation Metrics

Because of the severe class imbalance, model performance is evaluated using:

- Precision  
- Recall  
- F1-score  
- ROC-AUC  
- Confusion Matrix  

Accuracy is not considered a reliable metric for this problem.

---

## Results & Observations

- Logistic Regression provides a strong and interpretable baseline.
- The boosting model improves recall, which is critical in fraud detection scenarios.
- Model selection prioritizes recall and ROC-AUC over raw accuracy.

---

## Tools & Technologies

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## Conclusion

This project demonstrates that classical machine learning models, when combined with proper handling of class imbalance and suitable evaluation metrics, can effectively address real-world fraud detection problems.  
Model understanding and metric selection play a more important role than increasing model complexity.

---

## Future Improvements

- Hyperparameter tuning
- Threshold optimization for recall–precision trade-offs
- Model deployment as a real-time fraud detection service
