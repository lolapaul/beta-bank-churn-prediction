#  Beta Bank Churn Prediction

Predictive modeling project to identify customers likely to leave Beta Bank. The model is designed to assist the bank in improving customer retention strategies by identifying churn risk early.

---

##  Objective

Build and optimize a binary classification model that predicts whether a customer will leave the bank, maximizing the **F1 score**. The minimum acceptable threshold is F1 ≥ 0.59.

---

##  Dataset Description

The dataset includes 10,000+ customer records with the following features:

- `CreditScore`: Customer’s credit score
- `Geography`: Country of residence
- `Gender`: Customer’s gender
- `Age`: Age in years
- `Tenure`: Years with the bank
- `Balance`: Account balance
- `NumOfProducts`: Number of bank products used
- `HasCrCard`: Has a credit card (0/1)
- `IsActiveMember`: Active membership (0/1)
- `EstimatedSalary`: Estimated income
- `Exited`: Target variable (1 = churned, 0 = retained)

---

##  Project Workflow

1. **Data Preprocessing**
   - Clean and transform categorical and numerical variables
   - Encode features and scale data appropriately

2. **Class Imbalance Investigation**
   - Assess target distribution
   - Train baseline model without corrections

3. **Model Training and Tuning**
   - Compare Logistic Regression, Decision Tree, and Random Forest
   - Apply two balancing techniques: class weighting & oversampling
   - Tune hyperparameters and evaluate performance on validation set

4. **Final Evaluation**
   - Evaluate final model on test set
   - Compare **F1-score** and **AUC-ROC** metrics

---

##  Key Insights

- Explored the impact of customer demographics and product usage on churn
- Demonstrated the value of rebalancing strategies in improving F1 performance
- Delivered actionable predictions with interpretable models

---

##  Project Structure

```
beta-bank-churn-prediction/
│
├── beta_bank_churn_prediction.ipynb
├── Churn.csv
├── requirements.txt
└── README.md
```

---

##  Tools & Libraries Used

- Python
- pandas
- numpy
- matplotlib
- scikit-learn

---

##  Status

✔️ Project completed as part of the **TripleTen Bootcamp** – Sprint: *Binary Classification & Class Imbalance*

---

##  Author

David Villanueva  
[LinkedIn](https://www.linkedin.com/in/david-villanueva-59659727)  
[GitHub](https://github.com/lolapaul)
