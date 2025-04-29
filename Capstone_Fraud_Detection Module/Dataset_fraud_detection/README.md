# 🔍 Fraud Detection Using Machine Learning – Capstone Project

This repository contains the final-year capstone project focused on detecting fraudulent transactions using machine learning. The project involves exploratory data analysis, feature engineering, and modeling techniques to improve fraud detection accuracy and reduce false positives.

---

## 📌 Project Objectives

- Detect suspicious financial transactions with high accuracy
- Compare performance of multiple ML algorithms (e.g., XGBoost)
- Visualize fraud distribution and feature importance
- Integrate rule-based risk scoring with model predictions

---

## 📁 Project Structure

```
capstone-fraud-detection/
├── Capstone_finalYear_Project_FraudDetection.ipynb  # Main analysis notebook
├── README.md                                        # Project overview
├── data/                                            # Raw and processed data
├── outputs/                                         # Predictions, results
├── models/                                          # Saved models
└── visuals/                                         # Plots, screenshots
```

---

## 📊 Key Components

- **Data Preprocessing**: Handling missing values, encoding, and normalization
- **EDA & Visualization**:
  - Fraud vs non-fraud transaction distribution
  - Correlation heatmaps
  - Feature distributions
- **Feature Engineering**: Creating time-based and amount-based risk features
- **Modeling**: Training and evaluating ML models using:
  - XGBoost
  - Ensemble techniques
  - Threshold tuning for imbalanced classification
- **Rule-Based Risk Scoring**:
  - Custom rules layered on top of model predictions
  - Assigning risk levels to each transaction
- **Output**:
  - Final predictions merged with risk scores
  - CSV export for downstream usage

---

## 🧠 Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost
- Jupyter Notebook
- Google Colab

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/desaiaayush78/capstone-project-repo.git
   ```
2. Open the notebook in Google Colab or Jupyter:
   - Ensure required libraries are installed:
     ```bash
     pip install pandas xgboost scikit-learn matplotlib seaborn
     ```
3. Execute cells sequentially to reproduce results.

---

## 📈 Results

- XGBoost model achieved high accuracy on detecting fraudulent cases.
- Rule-based scoring added an explainable risk layer on top of predictions.
- Final dashboard-ready outputs were generated.

---

## 📌 Future Improvements

- Integrate real-time transaction API
- Add NLP-based adverse media analysis
- Deploy model using Flask or Streamlit

---

## 👤 Author

**Aayush Desai**  
Master’s in Data Science | Focused on Fraud Detection & Risk Analytics

---

## 📜 License

This project is open source under the [MIT License](https://choosealicense.com/licenses/mit/).
