# Telecom Customer Churn Analysis & Prediction

A comprehensive analytics solution to understand, visualize, and predict customer churn in the telecom industry.

---

##  Project Overview
**FinChurn** delivers a full-fledged analysis workflow, encompassing data ingestion, preprocessing, exploratory analysis, visualization, predictive modeling, and deployment via a user-friendly interface—all aimed at reducing churn and driving retention strategies.

---

##  Key Features & Workflow

### 1. Data Analysis Pipeline
- Loaded and cleansed telecom CSV datasets using Python (Pandas, NumPy).
- Conducted data preprocessing: handled missing entries, transformed variables, and addressed outliers.
- Generated new features (e.g., tenure groups, contract types, billing-related metrics) to strengthen churn insight.

### 2. Exploratory Data Analysis
- Analyzed churn distribution across demographics, services, and billing patterns.
- Highlighted correlations between churn and usage, tenure, payment methods, and service subscriptions.
- Identified high-risk customer segments based on spending and tenure.

### 3. Interactive Visualizations
- Built an interactive **Power BI dashboard** to display churn trends, retention hotspots, and segmentation analysis.
- Enables real-time tracking of churn metrics by demographics, contract types, and usage patterns.

### 4. Predictive Modeling
- Trained **Random Forest** (or Logistic Regression) model to classify churn risk.
- Achieved robust performance (e.g., accuracy, precision, recall), empowering proactive retention.

### 5. Deployment & Accessibility
- Created a **Streamlit app** for non-technical stakeholders to input customer details and receive instant churn predictions.
- Delivered seamless adoption by business users through an intuitive interface.

---

##  Repository Structure

├── data/
│ └── telecom_churn_data.csv # Raw telecom customer dataset
├── Telecom_EDA.ipynb # EDA notebook with preprocessing and visual analysis
├── TelecomDashboard.pbix # Power BI dashboard file for interactive visualization
├── Churn_Prediction_Model.ipynb # ML modeling notebook (training, validation, evaluation)
├── churn_model.pkl # Saved trained model object
├── scaler.pkl # Saved preprocessing scaler (if used)
├── ChurnApp.py # Streamlit application script for prediction
└── README.md # Project overview and documentation


---

##  Getting Started

1. **Clone the repository** to your local environment.
2. Launch `Telecom_EDA.ipynb` to load, clean, explore the data, and view visual insights.
3. Open `TelecomDashboard.pbix` in Power BI to interact with live dashboards tracking churn patterns.
4. Explore and evaluate the modeling pipeline in `Churn_Prediction_Model.ipynb`.
5. To use the prediction app, run:
   ```bash
   streamlit run ChurnApp.py


##  Repository Structure

