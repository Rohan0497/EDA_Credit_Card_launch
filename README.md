# EDA_Credit_Card_launch

# 💳 Credit Card Utilisation – Exploratory Data Analysis (EDA)

This project involves a detailed exploratory data analysis (EDA) of credit card user behavior. The goal is to uncover actionable insights into customer spending habits, credit limit usage, repayment behavior, and purchase patterns. These insights can inform feature engineering, customer segmentation, and serve as a foundation for future predictive modeling (e.g., churn or credit risk).

---

## 📌 Objectives

- Analyze utilization patterns, payment behavior, and customer activity levels.
- Identify inactive users and high-risk segments based on financial behavior.
- Visualize trends and correlations among key financial variables.
- Provide an interpretable basis for building downstream ML models.

---

## 📂 Dataset Overview

The dataset contains anonymized credit card usage data with the following features:

| Column | Description |
|--------|-------------|
| `BALANCE` | Current balance on the card |
| `CREDIT_LIMIT` | Credit limit assigned to the user |
| `PURCHASES` | Total amount of purchases |
| `ONEOFF_PURCHASES` | Purchases made in a single transaction |
| `INSTALLMENTS_PURCHASES` | Purchases made in installments |
| `PAYMENTS` | Total amount of payments made |
| `TENURE` | Number of months as a customer |
| `PURCHASE_TYPE` | Dominant type of purchase (One-off, Installment, None) |

> ⚠️ Note: This dataset is for educational and demonstrative purposes only.

---

## 🧪 Key Findings

- Over 45% of users had low or zero purchase activity, suggesting large segments of inactive accounts.
- More than 40% of customers had credit limits below \$2,000, indicating limited credit exposure or conservative lending.
- Strong correlation observed between `BALANCE`, `PAYMENTS`, and `CREDIT_LIMIT`.
- Users with predominantly one-off purchases showed different behavior compared to those using installment plans.
- Presence of outliers and skewed distributions in high-value financial features (e.g., `BALANCE`, `PAYMENTS`) indicate the need for preprocessing prior to ML modeling.

---

## 📈 Visualizations

- **Histograms** for balance, payments, and purchases.
- **Bar plots** and **pie charts** to assess customer segments and purchase types.
- **Correlation heatmaps** to reveal feature relationships.
- **Boxplots** for outlier detection.

All visualizations were generated using:

- **Seaborn**
- **Matplotlib**
- **Pandas**

---

## 🛠️ Technologies Used

- Python 3.9+
- Jupyter Notebook
- Pandas
- NumPy
- Seaborn
- Matplotlib

---

## 🚀 Getting Started

### 📦 Installation

1. **Clone the repository**
```bash
git clone https://github.com/your-username/credit-card-eda.git
cd credit-card-eda
```

2. **Create a virtual environment (optional but recommended)** 
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```

3. **Run the Jupyter notebook**
 ```bash
jupyter notebook Bank_credit_card_EDA.ipynb
```

