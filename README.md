# 🌾 Paddy Crop Data Analysis and Prediction

<p align="center">
  <strong>Turning Agricultural Data into Data-Driven Insights</strong>
  <br>
  A Supervised Machine Learning Regression Project
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge" alt="Seaborn">
  <img src="https://img.shields.io/badge/Domain-Agriculture-2E8B57?style=for-the-badge" alt="Agriculture">
</p>

---

## 🌱 1. Project Overview

### 📌 Problem Statement

Agriculture plays a vital role in food production and economic development. Paddy cultivation, in particular, depends on several agricultural factors, including soil characteristics, crop varieties, cultivated area, and farming practices.

Understanding how these factors influence crop yield can help identify meaningful patterns and support better agricultural decision-making.

This project focuses on analyzing paddy cultivation data and developing supervised machine learning regression models to predict paddy yield using agricultural features.

### 🎯 Project Objectives

- 🔍 Understand the dataset structure and its characteristics.
- 🧹 Identify missing values, duplicate records, and potential outliers.
- 📊 Perform Exploratory Data Analysis (EDA).
- 📈 Identify relationships between agricultural features and paddy yield.
- ⚙️ Apply data preprocessing and categorical encoding techniques.
- 🎯 Perform feature selection and feature scaling where appropriate.
- 🤖 Build and compare supervised machine learning regression models.
- 🛠️ Optimize model hyperparameters using cross-validation.
- 📉 Evaluate model performance using appropriate regression metrics.
- 🌾 Predict paddy yield based on agricultural information.

### 📋 Project Details

| Attribute | Description |
|---|---|
| **Project Title** | Paddy Crop Data Analysis and Prediction |
| **Domain** | Agriculture & Data Science |
| **Project Type** | Supervised Machine Learning – Regression |
| **Dataset Size** | 2,789 rows (before duplicate removal) |
| **Target Variable** | `Paddy yield(in Kg)` |
| **Student** | Harishraj R |
| **Batch** | DS-ANB-04 |

---

## 📂 2. Dataset Information

The dataset contains agricultural information related to paddy cultivation.

It includes information such as:

- Agricultural blocks
- Paddy varieties
- Soil types
- Nursery information
- Cultivated area
- Seed rate
- Fertilizer-related information
- Other agricultural and cultivation features

🔗 **Dataset:** [View and Download Paddy Dataset](https://raw.githubusercontent.com/HARISHRAJ-R-07/Project-dataset-csv-files/refs/heads/main/paddydataset.csv)

**Target Variable:** `Paddy yield(in Kg)`

The objective is to predict the numerical paddy yield using the available agricultural features.

---

## 🧰 3. Technologies & Libraries

| Technology | Purpose |
|---|---|
| Python | Programming and data analysis |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| SciPy | Statistical analysis |
| Scikit-learn | Machine learning and model evaluation |
| Google Colab | Development environment |

---

## 🔄 4. Project Workflow

The project follows a structured machine learning workflow:

```text
        📥 Dataset Collection
                 ↓
        🔍 Data Understanding
                 ↓
        📊 Exploratory Data Analysis
                 ↓
        🧹 Data Cleaning
                 ↓
        ⚙️ Data Preprocessing
                 ↓
        🎯 Feature Selection
                 ↓
        ✂️ Train-Test Split
                 ↓
        🤖 Model Training
                 ↓
        🛠️ Hyperparameter Tuning
                 ↓
        📈 Model Evaluation
                 ↓
        🌾 Paddy Yield Prediction
```

---

## 🔍 5. Exploratory Data Analysis (EDA)

Exploratory Data Analysis is performed to understand the dataset and discover meaningful agricultural patterns.

The analysis includes:

- Dataset shape and information
- Statistical summaries
- Missing value analysis
- Duplicate record identification
- Numerical feature distributions
- Categorical feature analysis
- Outlier detection
- Correlation analysis
- Relationship between agricultural features and paddy yield

---

## ⚙️ 6. Data Preprocessing

The following preprocessing techniques are considered:

- Handling duplicate records
- Checking and handling missing values
- Identifying potential outliers
- Encoding categorical variables
- Feature selection
- Feature scaling using StandardScaler
- Splitting data into training and testing sets

Preprocessing operations are fitted using training data where necessary to prevent data leakage.

---

## 🤖 7. Machine Learning Models

The project explores supervised machine learning regression algorithms, including:

- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**

Model performance is compared to identify a suitable approach for paddy yield prediction.

Hyperparameter optimization using `RandomizedSearchCV` and five-fold cross-validation can be used where implemented in the notebook.

---

## 📈 8. Model Evaluation Metrics

The regression models are evaluated using the following metrics:

| Evaluation Metric | Purpose |
|---|---|
| **MAE** – Mean Absolute Error | Measures the average absolute prediction error |
| **RMSE** – Root Mean Squared Error | Gives greater weight to larger prediction errors |
| **R² Score** | Measures how well the model explains the variation in paddy yield |

The final model should be selected based on cross-validation and unseen test-set performance.

---

## 📊 9. Visualizations

The `Visualizations/` directory contains plots generated during the data analysis and machine learning process.

Examples:

- Paddy yield distribution
- Correlation heatmap
- Numerical feature distributions
- Agricultural feature comparisons
- Feature relationships with paddy yield
- Model performance comparison

*Only include visualizations that have actually been generated and saved.*

---

## 📁 10. Repository Structure

```text
Paddy-Crop-Data-Analysis-and-Prediction/
│
├── Project_Notebook.ipynb
├── requirements.txt
├── README.md
│
└── Visualizations/
    ├── target_distribution.png
    ├── correlation_heatmap.png
    ├── feature_analysis.png
    └── model_comparison.png
```

---

## 🚀 11. Installation & Usage

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Navigate to the Project Folder

```bash
cd Paddy-Crop-Data-Analysis-and-Prediction
```

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

### Step 4: Open the Jupyter Notebook

```bash
jupyter notebook Project_Notebook.ipynb
```

Alternatively, open the notebook using Google Colab.

**Note:** An internet connection is required if the notebook downloads the dataset directly from the GitHub raw URL.

---

## 👨‍💻 12. Author

**Harishraj R**

*Aspiring Data Science Professional*

🎓 B.Sc. Computer Science and Data Science

🐙 **GitHub:** [HARISHRAJ-R-07](https://github.com/HARISHRAJ-R-07)

---

<p align="center">
  🌾 <strong>Exploring Data. Building Models. Supporting Smarter Agriculture.</strong>
  <br>
  <em>A hands-on journey into agricultural data analysis and machine learning.</em>
</p>
