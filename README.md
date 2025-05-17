# 💳 Credit Card Data Analysis Project

This project performs an exploratory data analysis (EDA) on a credit card dataset to uncover customer behaviors, repayment trends, and key financial metrics. It aims to generate business insights that can help financial institutions optimize credit risk assessment and customer targeting.

## 📁 Dataset Description

The dataset consists of three main CSV files:

- `customer_acquisition.csv` – Contains customer demographic and credit card type information.
- `spend.csv` – Records monthly spending patterns.
- `repayment.csv` – Contains repayment behavior per customer over time.

## 📊 Key Analyses Performed

### 1. **Utilization Ratio Calculation**
Measures how much of a customer's credit limit is used:
- `0.5` → 50% of credit limit used
- `1.0` → Fully maxed out

### 2. **Repayment Ratio Calculation**
Determines how much of their spending customers are repaying:
- `1.0` → Full repayment
- `0.5` → Partial repayment
- `0.0` → No repayment

### 3. **Over-Limit Flag**
Binary indicator for exceeding credit limit:
- `1` → Customer spent more than their limit
- `0` → Customer stayed within their limit

## 📈 Visualizations

### ✅ Monthly Spend vs Repayment
- Line plot comparing total monthly spend and repayments
- Business Insight: Reveals whether customers are generally repaying what they spend and highlights spikes of risky behavior.

### ✅ Distribution of Utilization Ratios
- Histogram with KDE overlay
- Business Insight: Most customers maintain low utilization, but there are a few outliers with extreme usage—potential credit risk indicators.

## 🧠 Business Insights

- Customers with high utilization and low repayment ratios may signal **default risk**.
- Majority of customers maintain a utilization ratio < 10, indicating **conservative credit usage**.
- Identifying over-limit behavior helps in **flagging high-risk profiles** early.
- Time-series trends reveal **seasonal spending spikes**, useful for forecasting and credit planning.

## 🛠️ Tools Used

- **Python**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook**

## 📌 Future Enhancements

- Build a machine learning model to **predict default risk**
- Create a **Streamlit or Dash dashboard** for business teams
- Integrate **SQL** for database-driven analysis
- Perform **customer segmentation** using clustering techniques

## 👤 Author

- **SamJ** – Chemical engineer and aspiring data scientist

---

