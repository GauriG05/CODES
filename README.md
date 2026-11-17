# Computer Laboratory I (CL-I) Practicals

This repository contains comprehensive practical implementations, datasets, and theoretical resources for **Machine Learning (ML)** and **Data Mining & Visualization (DMV)** as part of the Computer Laboratory I (CL-I) curriculum.

---

## 📁 Repository Structure

```text
├── DMV/                                # Data Mining & Visualization Practicals
│   ├── Practical 1.ipynb               # Data Exploration & Multi-format Loading (JSON, Excel, CSV)
│   ├── Practical 2.ipynb               # Weather Data Analysis (OpenWeatherMap API)
│   ├── Practical 3.ipynb               # Telecom Customer Churn Analysis
│   ├── Practical 4.ipynb               # Real Estate Market Data Wrangling & Outlier Removal
│   ├── Practical 5.ipynb               # Air Quality Index (AQI) Trend Analysis
│   ├── Practical 6.ipynb               # Retail Sales Performance Analysis
│   └── *.csv / *.xlsx / *.json         # Datasets for DMV practicals
│
├── ML/                                 # Machine Learning Practicals
│   ├── P1.ipynb                        # Principal Component Analysis (PCA) & Dimensionality Reduction
│   ├── P2.ipynb                        # Uber Fare Prediction (Linear, Ridge, & Lasso Regression)
│   ├── P3.ipynb                        # Support Vector Machine (SVM) Classification
│   ├── P4.ipynb                        # K-Means Clustering
│   ├── P5.ipynb                        # Random Forest Classifier & Model Evaluation
│   ├── P6.ipynb                        # Reinforcement Learning (Q-Learning Maze Navigation)
│   └── *.csv                           # Datasets for ML practicals
│
├── CL-I Lab Manual 2025-26.pdf         # Official Lab Manual
├── DMV_Practicals_theory.pdf           # DMV Practical Theory Notes
├── ML_Practicals_Theory.pdf            # ML Practical Theory Notes
├── .gitignore                          # Standard Python / Jupyter gitignore
└── README.md                           # Documentation
```

---

## 🧪 Machine Learning (ML) Practicals

| Practical | Title | Description | Dataset |
| :--- | :--- | :--- | :--- |
| **P1** | Principal Component Analysis | Dimensionality reduction, feature scaling, and visualization using PCA | `Iris.csv`, `Wine.csv` |
| **P2** | Uber Fare Prediction | Price prediction using Linear Regression, Ridge, and Lasso with IQR outlier filtering and StandardScaler | `uber.csv` |
| **P3** | SVM Classification | Non-linear classification and hyperparameter tuning using Support Vector Machines | `car_evaluation.csv` |
| **P4** | K-Means Clustering | Unsupervised clustering, elbow method for optimal *k*, and cluster visualization | `Iris.csv` |
| **P5** | Random Forest Classifier | Ensemble learning, feature importance, confusion matrix, and classification report | `car_evaluation.csv` |
| **P6** | Reinforcement Learning | Q-learning algorithm implementation for pathfinding in a maze environment | Simulated Grid/Maze |

---

## 📊 Data Mining & Visualization (DMV) Practicals

| Practical | Title | Description | Dataset |
| :--- | :--- | :--- | :--- |
| **Practical 1** | Data Preprocessing & Ingestion | Reading and wrangling CSV, JSON, and Excel formats; handling missing values | `customers.json`, `Sample-Sales-Data.xlsx`, `iris.csv` |
| **Practical 2** | Weather Data Analysis | Exploratory analysis on atmospheric conditions, temperature variations, and distributions | OpenWeatherMap / Weather data |
| **Practical 3** | Customer Churn Analysis | EDA, churn indicators, correlation heatmaps, and demographic analysis | `Cleaned_Telecom_Customer_Churn.csv` |
| **Practical 4** | Real Estate Data Wrangling | Handling outliers, location grouping, feature engineering, and price-per-sqft analysis | `Bengaluru_House_Data.csv`, `bhp.csv` |
| **Practical 5** | Air Quality Index (AQI) Trends | Time-series and pollutant level trends (PM2.5, PM10, NO2, CO) | `AirQuality.csv` |
| **Practical 6** | Retail Sales Performance | Regional sales performance, product trends, and revenue distributions | `data.csv`, `sales_data_sample.csv` |

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.8+ installed.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/GauriG05/CODES.git
   cd CODES
   ```

2. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install required packages:**
   ```bash
   pip install notebook pandas numpy matplotlib seaborn scikit-learn openpyxl
   ```

4. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

---

## 📚 Reference Materials

- **CL-I Lab Manual 2025-26.pdf**: Course syllabus, lab assignments, and guidelines.
- **DMV_Practicals_theory.pdf**: Theory concepts and background for Data Mining & Visualization.
- **ML_Practicals_Theory.pdf**: Mathematical and conceptual background for Machine Learning algorithms.
