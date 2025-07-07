# 🌱 CO₂ Emission Predictor

### Using Machine Learning to Model and Predict Environmental Impact

### Shell–Edunet Foundation – AICTE Virtual Internship

---

## 🧠 Problem Statement

The goal of this project is to analyze country-specific historical data and develop machine learning models to predict CO₂ emissions based on various national parameters. The dataset comes from the World Bank Group's Climate Change Data, covering 1990 to 2011 and including information on:

- Greenhouse gases (CO₂, CH₄, N₂O)
- Population metrics (total, urban %, growth rate)
- Economic indicators (GDP, GNI, FDI)
- Land and agriculture (cereal yield, protected areas)
- Climate and energy usage
- Medical infrastructure

The project is divided into **three stages**, each documented in separate Jupyter Notebooks.

---

## 📅 Project Timeline and Stages

### ✅ **Stage 1: Data Cleaning and Preparation**

**Notebook:** `data_preparation.ipynb`

#### Key Steps:

- Overview of raw data and initial objectives
- Import libraries and load datasets
- Clean and transform data:
  - Handle missing values
  - Standardize data types
  - Rename and restructure features
- Melt and integrate data into a unified format
- Final cleaning and export to CSV

**Output:** A clean, analysis-ready dataset saved in CSV format.

---

### ✅ **Stage 2: Data Exploration and Visualization**

**Notebook:** `data_exploration.ipynb`

#### Key Steps:

- Introduce hypothesis and data scope
- Feature engineering and transformation
- Removal of irrelevant features
- Visual exploration of data:
  - Correlation heatmaps
  - Scatterplots, histograms
  - Trend lines and outlier detection
- Analytical commentary on observed patterns

**Outcome:** Insight into variable relationships and dependencies affecting CO₂ emissions.

---

### ✅ **Stage 3: Predictive Modeling and Evaluation**

**Notebook:** `model_building.ipynb`

#### Key Steps:

- Define modeling goal and ML strategy
- Select features and define target variable (CO₂ emissions)
- Train-test split and preprocessing
- Feature selection using Recursive Feature Elimination (RFE)
- Hyperparameter tuning (Random Forest)
- Model training and cross-validation
- Performance metrics:
  - R² Score
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Squared Error)
- Final model validation and conclusions

**Best Performing Model:** Random Forest Regressor with optimized hyperparameters

---

## 📦 Model Access

You can download the trained machine learning model from the link below:

🔗 [Download Trained Model (Google Drive)](https://drive.google.com/file/d/1C-PhET4KZuLP_Uj7y9HvpuExwxzgK-0o/view?usp=sharing)

> Includes serialized model files (e.g., `.pkl`, `.joblib`) from the best-performing algorithm (Random Forest Regressor).

---


## 🌍 Dataset Summary

**Source:** [World Bank Climate Change Data (1990–2011)](https://datacatalog.worldbank.org/dataset/climate-change-data)\
**License:** [Creative Commons Attribution 4.0 International License](https://datacatalog.worldbank.org/public-licenses#cc-by)

Key data groups:

- 🌫️ Emissions: CO₂, CH₄, N₂O
- 👥 Population: total, urban %, growth
- 💰 Economics: GDP, GNI, FDI
- ⚡ Energy usage
- 🌾 Agriculture and land use
- ☁️ Climate patterns and disasters
- 🏥 Health infrastructure

---

## 🛠️ Tech Stack

| Purpose       | Tools / Libraries                   |
| ------------- | ----------------------------------- |
| Data Cleaning | Python, Pandas, NumPy               |
| Visualization | Matplotlib, Seaborn                 |
| Modeling      | Scikit-learn, XGBoost, RandomForest |
| Development   | Jupyter Notebook                    |
| Data Format   | Excel (raw), CSV (cleaned)          |

---

## 🚀 How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/charan11640/CarbonEmission-Prediction.git
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the Jupyter Notebooks:**

   ```bash
   jupyter notebook data_preparation.ipynb   # Data cleaning
   jupyter notebook data_exploration.ipynb   # EDA and visualization
   jupyter notebook model_building.ipynb  # Modeling and evaluation
   ```

---

## ✨ Future Enhancements

- 📊 Add time-series forecasting (e.g., ARIMA, Prophet)
- 📊 Build an interactive dashboard using Streamlit or Plotly Dash
- 🌐 Integrate real-time datasets using APIs
- 🐳 Dockerize the project for containerized deployment
- 🚂 Implement CI/CD pipelines with GitHub Actions
- 🧢 Add automated unit testing using Pytest

---

## 👨‍💼 Author

**Kuna Charan Sai**\
B.Tech (Information Technology) – Final Year @ SIR CR REDDY COLLEGE OF ENGINEERING\
🎓 Summer Intern @ Shell–Edunet Foundation\
📧 [charansaikuna11640@gmail.com](mailto\:charansaikuna11640@gmail.com)

---
