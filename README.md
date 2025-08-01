# 📊 Customer Churn Analysis & Prediction – End-to-End Project
## 📊 Project Overview

Complete churn analysis & prediction pipeline using SQL, Python, Power BI.

---

## 🎥 Dashboard Walkthrough Video 
[Click here to watch video walkthrough (Google Drive)](https://drive.google.com/file/d/1b2tfX8ftiHhthxvlS8csNUHlZwtfiBTQ/view?usp=sharing)


This portfolio project demonstrates a complete churn analysis and prediction pipeline using:

- **SQL Server** for ETL  
- **Power BI** for interactive dashboards  
- **Python** (Random Forest) for predictive modeling  

---

## 📁 Project Structure

- `sql/` – Scripts for creating databases, cleaning, and preparing data  
- `notebook/` – Python notebook for building the churn prediction model  
- `powerbi/` – Power BI `.pbix` file and dashboard screenshots  
- `data/` – Sample input files and prediction outputs  

---

## 🎯 Project Objectives

✅ Visualize and analyze churn by demographics, geography, account info, and services  
✅ Create dashboards for business users  
✅ Build a churn prediction model using Random Forest  
✅ Load prediction results into Power BI for actionable insights  

---

## 📌 Tools & Technologies

- Microsoft SQL Server + SSMS  
- Microsoft Power BI  
- Python 3.10 (Jupyter Notebook)  
- Libraries: `pandas`, `scikit-learn`, `seaborn`, `joblib`, `matplotlib`  

---

## 🧠 Machine Learning Model

- **Model**: `RandomForestClassifier`  
- **Target**: `Customer_Status` (Churned vs Stayed)  
- **Key Features**: Contract, Internet Type, Revenue, Tenure, etc.  
- **Evaluation**: Confusion matrix, classification report, feature importance  

---

## 📊 Dashboard Preview

📍 Summary Page  
📍 Churn Prediction Page  

🖼️ [View Power BI Dashboards – Screenshot 1](https://drive.google.com/uc?id=1Kj59zirWaMiO8ynBjm49NSNjFd4MThKM)  
🖼️ [View Power BI Dashboards – Screenshot 2](https://drive.google.com/uc?id=1Et-gO3VYu_I54jELCPjMLnNakbV3Vr9D)

---

## 🧪 How to Run

### 1. SQL Setup
- Run the scripts in `sql/` to:
  - Create the database `db_Churn`
  - Load and clean data
  - Create views: `vw_ChurnData`, `vw_JoinData`

### 2. Power BI Dashboard
- Open `churn_dashboard.pbix`  
- Connect to SQL Server or use local CSV as data source  
- Explore pre-built visuals and KPIs  

### 3. Python Model (ML Prediction)
- Install dependencies:
  ```bash
  pip install -r requirements.txt
