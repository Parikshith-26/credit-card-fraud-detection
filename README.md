# 🛡️ Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent credit card transactions using machine learning. The goal is to accurately identify frauds from a highly imbalanced dataset and minimize false positives and false negatives.

## 📌 Objective

To build a machine learning model that can detect credit card fraud by analyzing transaction patterns, with high precision and recall.

## 🧠 Technologies Used

- Python
- Pandas & NumPy (Data Handling)
- Matplotlib & Seaborn (Visualization)
- Scikit-learn (Model Building & Evaluation)
- Jupyter Notebook / Google Colab

## 📂 Dataset

- **Source**: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Records**: 284,807 transactions
- **Fraud Cases**: ~0.17% of the data
- Features: `Time`, `Amount`, `V1` to `V28`, and `Class` (target variable)

## ⚙️ Project Workflow

1. **Import Libraries**  
2. **Load and Explore the Dataset**  
3. **Visualize Class Imbalance and Correlations**  
4. **Compare Fraudulent and Valid Transactions**  
5. **Split Data into Training and Testing Sets**  
6. **Train a Random Forest Classifier**  
7. **Evaluate the Model using Accuracy, Precision, Recall, F1-Score, and MCC**  
8. **Visualize Confusion Matrix**

## 📊 Model Performance

- **Precision**: 98.73%  
- **Recall**: 79.59%  
- **F1-Score**: 88.14%  
- **Accuracy**: 99.96%  
- **MCC**: 0.8863  

> ⚠️ *Note: Accuracy alone is misleading due to class imbalance. Precision and recall are more meaningful.*

## 📈 Confusion Matrix

The confusion matrix visualizes how well the model distinguishes between fraudulent and non-fraudulent transactions.

## 📝 Conclusion

This model effectively detects fraudulent transactions with high precision while maintaining a good balance with recall. Future improvements could include:
- Trying different models like XGBoost or Autoencoders
- Using resampling techniques like SMOTE
- Building a real-time fraud detection pipeline

## 🙋‍♂️ Author

**Parikshith VM**  
Feel free to connect or contribute!

---

