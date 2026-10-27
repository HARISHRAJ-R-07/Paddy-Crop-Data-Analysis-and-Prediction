# 🌾 Paddy Crop Data Analysis and Prediction

<p align="center">
  <strong>Turning Agricultural Data into Data-Driven Insights</strong>
  <br>
  A Supervised Machine Learning Regression Project
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/Domain-Agriculture-2E8B57?style=for-the-badge" alt="Agriculture">
</p>

---

## 🌱 1. Project Overview

### 📌 Problem Statement

Paddy cultivation plays an important role in agriculture and food production. Understanding the relationship between agricultural factors and crop yield can help identify meaningful patterns and support data-driven farming decisions.

This project explores paddy cultivation data and applies **supervised machine learning regression algorithms** to predict paddy yield using agricultural features.

### 🎯 Project Objectives

- 🔍 Explore the dataset and understand its structure.
- 🧹 Identify missing values, duplicate records, and potential outliers.
- 📊 Analyze relationships between agricultural features and paddy yield.
- ⚙️ Perform data cleaning, categorical encoding, and feature selection.
- 🤖 Train and compare regression models.
- 📈 Evaluate model performance on unseen test data.
- 🛠️ Tune model hyperparameters using cross-validation.

### 📋 Project Details

| Attribute | Description |
|---|---|
| **Project Title** | Paddy Crop Data Analysis and Prediction |
| **Domain** | Agriculture & Data Science |
| **Project Type** | Supervised Machine Learning — Regression |
| **Target Variable** | `Paddy yield(in Kg)` |
| **Student** | Harishraj R |
| **Batch** | DS-ANB-04 |

---

## 📂 2. Dataset Information

The dataset contains agricultural information related to paddy cultivation, including agricultural blocks, paddy varieties, soil types, cultivated area, and other cultivation-related features.

🔗 **Dataset:** [View and download the Paddy Dataset](https://raw.githubusercontent.com/HARISHRAJ-R-07/Project-dataset-csv-files/refs/heads/main/paddydataset.csv)

**Target variable:** `Paddy yield(in Kg)`

The regression models aim to predict this numerical target using the available agricultural features.

---

## 🧰 3. Technologies & Libraries

| Technology | Purpose |
|---|---|
| Python | Programming and analysis |
| Pandas & NumPy | Data manipulation and numerical operations |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn | Machine learning and model evaluation |
| SciPy | Statistical analysis |
| Jupyter Notebook / Google Colab | Development environment |

---

## 🔄 4. Project Workflow

```text
       📥 Dataset Collection
                ↓
       🔍 Data Understanding
                ↓
       📊 Exploratory Data Analysis
                ↓
       🧹 Data Cleaning & Preprocessing
                ↓
       ⚙️ Encoding & Feature Selection
                ↓
       ✂️ Train-Test Split
                ↓
       🤖 Model Training & Comparison
                ↓
       🛠️ Hyperparameter Tuning
                ↓
       📈 Model Evaluation
                ↓
       🌾 Paddy Yield Prediction
```

---

## 🤖 5. Machine Learning Models

The project compares the following regression algorithms:

- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**

Hyperparameter optimization is performed using `RandomizedSearchCV` with five-fold cross-validation.

The final model is selected based on cross-validation results and performance on unseen test data.

---

## 📈 6. Model Evaluation Metrics

| Metric | Purpose |
|---|---|
| **MAE** — Mean Absolute Error | Measures the average absolute prediction error |
| **RMSE** — Root Mean Squared Error | Penalizes larger prediction errors more strongly |
| **R² Score** | Measures how well the model explains target variability |

The evaluation results help compare the models and identify a suitable approach for paddy yield prediction.

---

## 📊 7. Visualizations

The `Visualizations/` folder contains plots created during exploratory data analysis and model evaluation.

Examples include:

- Distribution of paddy yield
- Correlation heatmap
- Agricultural feature distributions
- Relationships between selected features and paddy yield
- Model evaluation visualizations, where available

*Only include plots that have actually been generated and saved in the repository.*

---

## 📁 8. Repository Structure

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
    └── other_eda_plots.png
```

---

## 🚀 9. Installation & Usage

### Step 1: Clone the Repository

Replace the placeholder with your actual GitHub repository URL.

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd Paddy-Crop-Data-Analysis-and-Prediction
```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Launch the Notebook

```bash
jupyter notebook Project_Notebook.ipynb
```

Alternatively, open the notebook in **Google Colab** and execute the cells in order.

> **Note:** The notebook retrieves the dataset from GitHub using its raw URL, so an internet connection is required.

---

## 👨‍💻 10. Author

**Harishraj R**  
*Aspiring Data Science Professional*

- 🐙 **GitHub:** [HARISHRAJ-R-07](https://github.com/HARISHRAJ-R-07)

---

<p align="center">
  🌾 <strong>Exploring Data. Building Models. Supporting Smarter Agriculture.</strong>
  <br>
  <em>A hands-on project in data analysis and supervised machine learning.</em>
</p>
