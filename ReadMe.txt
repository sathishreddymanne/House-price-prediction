# 🏡 House Price Prediction

### Machine Learning-Based House Price Prediction using Regression Algorithms

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

# 📌 Overview

## 📖 Project Overview

The **House Price Prediction** project aims to predict residential property prices using Machine Learning regression algorithms.

Real estate prices depend on several factors such as **location, area, number of bedrooms, bathrooms, balconies, and total square footage**. This project demonstrates a complete Machine Learning workflow—from **data preprocessing** and **feature engineering** to **model training**, **evaluation**, and **comparison**.

The objective is to identify the regression model that provides the most accurate house price predictions while following industry-standard Data Science practices.

---

# 🎯 Objectives

- ✅ Clean and preprocess housing data.
- ✅ Perform feature engineering and outlier analysis.
- ✅ Train multiple Machine Learning regression models.
- ✅ Compare model performance using evaluation metrics.
- ✅ Select the best-performing model for price prediction.

---

# 📊 Dataset

The dataset contains information about residential properties.

## Features

| Feature | Description |
|----------|-------------|
| Area Type | Type of residential area |
| Availability | Property availability status |
| Location | Property location |
| Size | Number of Bedrooms (BHK) |
| Total Square Feet | Total built-up area |
| Bathrooms | Number of bathrooms |
| Balconies | Number of balconies |
| Price | Target Variable |

---

# 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns.
- Handled missing values.
- Removed the **society** column due to excessive missing values.
- Extracted **BHK** values from the **size** column.
- Converted **total_sqft** into numerical values.
- Removed duplicate and inconsistent records.
- Encoded categorical variables.
- Detected and removed outliers using the **IQR Method**.
- Prepared the dataset for Machine Learning.

---

# ⚙️ Feature Engineering

## Input Features

- BHK
- Total Square Feet
- Bathrooms
- Balconies
- Encoded Location
- Encoded Area Type

## Target Variable

- Price

---

# 📈 Exploratory Data Analysis

Various visualization techniques were used to understand the dataset.

### Analysis Performed

- Distribution Plots
- Correlation Heatmap
- Boxplots
- Outlier Analysis
- Feature Relationships

### Example Visualizations

> Add your screenshots inside the **images/** folder.

```markdown
![Correlation Heatmap](images/heatmap.png)

![Boxplot](images/boxplot.png)

![Model Comparison](images/model_comparison.png)
```

---

# 🤖 Machine Learning Models

The following regression algorithms were implemented.

| Model |
|--------|
| Linear Regression |
| Decision Tree Regressor |
| Random Forest Regressor |
| K-Nearest Neighbors (KNN) Regressor |
| Support Vector Regressor (SVR) |

---

# ⚖️ Feature Scaling

**StandardScaler** was applied to normalize numerical features before training models that are sensitive to feature scales.

---

# 📏 Model Evaluation

The models were evaluated using the following metrics.

- 📌 R² Score
- 📌 Mean Absolute Error (MAE)
- 📌 Mean Squared Error (MSE)

---

# 🏆 Results

| Model | R² Score | MAE | MSE |
|--------|---------:|----:|----:|
| Linear Regression | XX | XX | XX |
| Decision Tree | XX | XX | XX |
| Random Forest | XX | XX | XX |
| KNN | XX | XX | XX |
| SVR | XX | XX | XX |

## ⭐ Best Model

> **Random Forest Regressor** achieved the best performance based on the evaluation metrics and was selected as the final prediction model.

*(Update this section if another model performs better.)*

---

# 🔄 Machine Learning Workflow

```text
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Missing Value Handling
   │
   ▼
Feature Engineering
   │
   ▼
Outlier Detection
   │
   ▼
Encoding
   │
   ▼
Feature Scaling
   │
   ▼
Train-Test Split
   │
   ▼
Model Training
   │
   ▼
Model Evaluation
   │
   ▼
Performance Comparison
   │
   ▼
Best Model Selection
```

---

# 📂 Project Structure

```text
House-Price-Prediction/
│
├── dataset/
│   └── Bengaluru_House_Data.csv
│
├── notebooks/
│   └── HousePricePrediction.ipynb
│
├── images/
│   ├── heatmap.png
│   ├── boxplot.png
│   └── model_comparison.png
│
├── outputs/
│
├── requirements.txt
│
├── README.md
│
└── LICENSE
```

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Matplotlib | Visualization |
| Seaborn | Statistical Visualization |
| Scikit-Learn | Machine Learning |
| Jupyter Notebook | Development Environment |

---

# 📦 Installation

Clone the repository.

```bash
git clone https://github.com/yourusername/House-Price-Prediction.git
```

Navigate to the project directory.

```bash
cd House-Price-Prediction
```

Install the required packages.

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook.

```bash
jupyter notebook
```

---

# ▶️ Usage

1. Open the notebook.
2. Load the dataset.
3. Execute all notebook cells.
4. Train the regression models.
5. Compare evaluation metrics.
6. Predict house prices using the best-performing model.

---

# 📚 Python Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

# 💡 Key Learnings

This project provided hands-on experience in:

- Data Cleaning
- Missing Value Handling
- Feature Engineering
- Exploratory Data Analysis
- Outlier Detection
- Feature Scaling
- Regression Algorithms
- Model Evaluation
- End-to-End Machine Learning Pipeline Development

---

# 🚀 Future Improvements

- Hyperparameter Tuning using GridSearchCV
- Implement XGBoost and LightGBM
- Deploy using Flask or FastAPI
- Build an interactive Streamlit Web Application
- Containerize using Docker
- Add Model Explainability with SHAP/LIME
- Automate model retraining using CI/CD pipelines

---

# 👨‍💻 Author

**Sathish Reddy Manne**

AI & ML Student • Machine Learning Enthusiast • Aspiring Data Scientist

- GitHub: https://github.com/yourusername
- LinkedIn: https://linkedin.com/in/yourprofile

---

# 🙏 Acknowledgements

- Scikit-Learn Documentation
- Pandas Documentation
- NumPy Documentation
- Matplotlib Documentation
- Seaborn Documentation

Special thanks to the open-source community for providing the amazing tools and libraries used in this project.

---

# ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star** on GitHub. It motivates future improvements and helps others discover the project.
