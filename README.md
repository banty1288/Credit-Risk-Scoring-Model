# 💳 Credit Score & Loan Risk Prediction System

An end-to-end Machine Learning project that predicts loan default risk, generates credit scores, categorizes borrowers into risk groups, and provides data-driven loan decision recommendations using financial and behavioral indicators.

---

## 📌 Project Overview

Credit risk assessment is one of the most important applications of machine learning in the financial industry. Traditional credit scoring methods often struggle to evaluate borrowers with limited or non-traditional credit histories.

This project demonstrates how machine learning can be used to assess borrower risk by analyzing financial and behavioral characteristics. The developed system estimates the probability of loan default, transforms predictions into interpretable credit scores, assigns risk categories, and recommends lending decisions.

> **Note:** This project uses a synthetic dataset created for educational and portfolio purposes.

---

## 🎯 Problem Statement

Financial institutions need reliable methods to identify high-risk borrowers while ensuring fair access to credit.

The objective of this project is to develop a machine learning pipeline capable of:

- Predicting the likelihood of loan default,
- Generating understandable credit scores,
- Categorizing applicants into different risk groups,
- Supporting lending decisions using data-driven insights.

---

## 🚀 Project Highlights

✔ Built an end-to-end credit risk prediction workflow.

✔ Compared multiple machine learning classification algorithms.

✔ Developed a credit score generation framework ranging from **300–900**.

✔ Created a risk categorization system for borrower segmentation.

✔ Designed a loan recommendation framework based on predicted risk.

---

## 📂 Repository Structure

```text
credit-score-prediction/
│
├── EDA.ipynb
├── ModelSelection.ipynb
├── synthetic_credit_data_v2.csv
├── README.md
└── requirements.txt
```

| File | Description |
|-------|-------------|
| `EDA.ipynb` | Exploratory Data Analysis and visualization |
| `ModelSelection.ipynb` | Model development, evaluation, and comparison |
| `synthetic_credit_data_v2.csv` | Synthetic dataset used for experimentation |
| `README.md` | Project documentation |
| `requirements.txt` | Required Python dependencies |

---

## 📊 Dataset Information

The project utilizes a synthetic dataset designed to simulate lending scenarios involving borrowers with varying financial characteristics.

### Dataset Characteristics

| Attribute | Value |
|-----------|---------|
| Number of Records | 10,000 |
| Problem Type | Binary Classification |
| Target Variable | Loan Status |

### Target Variable

| Value | Meaning |
|--------|----------|
| 0 | Repaid |
| 1 | Default |

### Features Included

Examples of variables used in the project include:

- Age
- Monthly Income
- Employment Type
- Existing Loan Amount
- Debt-to-Income Ratio
- Credit Utilization Ratio
- Savings Balance
- Number of Credit Accounts
- Repayment History
- Financial Stability Indicators

---

## 🔍 Exploratory Data Analysis (EDA)

The EDA phase focused on understanding borrower behavior and identifying factors associated with loan default.

### Analyses Performed

- Missing value assessment
- Descriptive statistical analysis
- Feature distribution analysis
- Correlation analysis
- Class distribution inspection
- Credit score visualization
- Risk category analysis

---

## 🤖 Machine Learning Models Evaluated

Several classification algorithms were trained and evaluated.

| Model | Accuracy |
|---------|-----------|
| Logistic Regression | 90.75% |
| Decision Tree | 90.55% |
| Random Forest | **90.85%** |

---

## 🏆 Final Model Selection

### Random Forest Classifier

The Random Forest model demonstrated the best overall performance and was selected as the final model.

### Model Performance

| Metric | Score |
|---------|--------|
| Accuracy | **90.85%** |
| ROC-AUC Score | **0.827** |
| Recall (Default Class) | **0.69** |

### Why Random Forest?

- Handles non-linear relationships effectively.
- Reduces overfitting through ensemble learning.
- Provides robust performance with minimal feature engineering.
- Performs well on structured tabular datasets.

---

## 💳 Credit Score Generation

Predicted probabilities from the final model were transformed into an interpretable **credit score ranging from 300 to 900**.

### Credit Score Statistics

| Statistic | Value |
|------------|--------|
| Mean | 771.10 |
| Standard Deviation | 179.06 |
| Minimum | 307 |
| Median | 852 |
| Maximum | 892 |

---

## ⚠️ Risk Categorization

Borrowers were segmented into risk groups based on their generated credit scores.

| Risk Category | Count |
|---------------|--------|
| Excellent | 7,865 |
| Low Risk | 414 |
| Moderate Risk | 186 |
| High Risk | 1,535 |

---

## 🏦 Loan Decision Recommendations

Based on predicted risk levels, the system provides lending recommendations.

| Recommendation | Count |
|---------------|--------|
| Approve | 8,118 |
| Approve with Monitoring | 161 |
| Manual Review | 186 |
| Reject | 1,535 |

---

## 🛠️ Tech Stack

### Programming Language

- Python

### Libraries Used

- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📈 Workflow

```text
Data Collection
        ↓
Data Cleaning & Preparation
        ↓
Exploratory Data Analysis
        ↓
Feature Selection
        ↓
Train-Test Split
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Model Comparison
        ↓
Credit Score Generation
        ↓
Risk Categorization
        ↓
Loan Decision Recommendation
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/banty1288/credit-score-prediction.git

cd credit-score-prediction
```

---

### 2. Create a Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Run the notebooks sequentially:

1. `EDA.ipynb`
2. `ModelSelection.ipynb`

---

## 📦 Requirements

Create a `requirements.txt` file containing:

```text
numpy
pandas
matplotlib
scikit-learn
jupyter
```

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## 📚 Key Learnings

This project provided hands-on experience in:

- Exploratory Data Analysis (EDA)
- Classification model development
- Model comparison techniques
- Ensemble learning methods
- Credit risk analytics
- Translating machine learning outputs into business decisions
- Building recruiter-ready machine learning projects

---

## 🔮 Future Improvements

Potential enhancements include:

- Hyperparameter optimization using GridSearchCV.
- Integration of explainable AI techniques such as SHAP.
- Development of a Streamlit-based user interface.
- Deployment using Flask or FastAPI.
- Integration with real-world financial datasets.
- Automated retraining pipelines.

---

## ⚠️ Disclaimer

This project was developed solely for educational and portfolio purposes.

The dataset used in this repository is synthetic and does not contain real customer information. Consequently, the generated predictions and recommendations should **not** be used for actual lending decisions without extensive validation, regulatory review, and testing on real-world financial data.

---

## 👨‍💻 Author

### Banty Kumar

Aspiring **Machine Learning Engineer** passionate about building practical machine learning solutions that solve real-world problems through data-driven decision making.

### Connect with Me

- GitHub: https://github.com/banty1288
- LinkedIn: https://www.linkedin.com/in/banty-kumar-746927372/

I am continuously learning and building projects in Machine Learning, Data Science, and Artificial Intelligence. Feedback, suggestions, and collaboration opportunities are always welcome.

---

## ⭐ Support

If you found this project useful or interesting, please consider giving the repository a **star**.

It helps increase the visibility of the project and motivates me to continue building and sharing machine learning projects.

---
