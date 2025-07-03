# Healthcare Patient Risk Prediction

This project focuses on predicting healthcare patient risk using machine learning and visualizing insights using Power BI. It provides an end-to-end data science solution from model training to dashboarding.

## 📁 Project Structure

Healthcare-Patient-Risk-Prediction/
├── data/
│ └── patient_data.csv
├── notebooks/
│ └── healthcare_patient_risk_prediction.ipynb
├── powerbi/
│ └── healthcare_dashboard.pbix
└── README.md


## 📝 Problem Statement

Predict whether a patient is at high risk (1) or low risk (0) based on features such as age, medical history, and other clinical variables. The objective is to assist healthcare providers in identifying high-risk patients proactively.

## ⚙️ Tools & Technologies

- Python (Google Colab): pandas, scikit-learn, matplotlib, seaborn
- Power BI: Interactive visualizations and dashboards
- GitHub: Version control

## 🚀 Project Workflow

### 1️⃣ Data Preparation
- Loaded dataset (`patient_data.csv`)
- Performed missing value handling
- Conducted exploratory data analysis (EDA)
- Feature engineering: encoded categorical variables, scaled numerical features

### 2️⃣ Model Building
- Split data into train/test sets
- Applied Logistic Regression for classification
- Evaluated using accuracy score and confusion matrix

### 3️⃣ Power BI Dashboard
- Visualizations:
  - Age group vs risk (bar chart / scatter plot)
  - Predicted risk vs actual risk (stacked / clustered bar chart)
  - Risk distribution across age groups
- KPIs showing overall % of high-risk patients

## 💻 How to Run

1. **Colab Notebook**
   - Open `notebooks/healthcare_patient_risk_prediction.ipynb` in Google Colab
   - Run all cells to reproduce results

2. **Power BI**
   - Open `powerbi/healthcare_dashboard.pbix` in Power BI Desktop
   - Refresh data if required

## 📂 Files in Repository

- `notebooks/healthcare_patient_risk_prediction.ipynb` — Model building code
- `data/patient_data.csv` — Dataset used (or link if private)
- `powerbi/healthcare_dashboard.pbix` — Power BI dashboard
- `README.md` — Project description

## 📌 Future Improvements

- Implement advanced models (Random Forest, XGBoost)
- Hyperparameter tuning
- Add more clinical features
- Deploy as a web app or API

## ✉️ Contact

Author: Nandini Devadiga
Email: nandinideepa16@gmail.com
