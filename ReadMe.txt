 🏡 House Price Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

📌 Project Overview

The **House Price Prediction** project aims to predict residential property prices using Machine Learning regression algorithms. Real estate prices depend on several factors such as location, area, number of bedrooms, bathrooms, balconies, and total square footage. This project demonstrates a complete Machine Learning workflow—from data preprocessing and feature engineering to model training, evaluation, and comparison.

The objective is to identify the regression model that provides the most accurate price predictions while following industry-standard data science practices.

---

🎯 Objectives

* Clean and preprocess housing data.
* Perform feature engineering and outlier analysis.
* Train multiple regression models.
* Compare model performance using evaluation metrics.
* Select the best-performing model for price prediction.

---

 📊 Dataset

The dataset contains information about residential properties.

Features

| Feature           | Description                  |
| ----------------- | ---------------------------- |
| Area Type         | Type of residential area     |
| Availability      | Property availability status |
| Location          | Property location            |
| Size              | Number of bedrooms (BHK)     |
| Total Square Feet | Total built-up area          |
| Bathrooms         | Number of bathrooms          |
| Balconies         | Number of balconies          |
| Price             | Target variable              |

---

🧹 Data Preprocessing

The following preprocessing steps were performed:

* Removed unnecessary columns.
* Handled missing values.
* Removed the **society** column due to excessive missing data.
* Extracted BHK values from the **size** column.
* Converted **total_sqft** into numerical values.
* Removed duplicate and inconsistent records.
* Encoded categorical variables.
* Detected and removed outliers using the IQR method.
* Prepared the dataset for Machine Learning.

---

 ⚙️ Feature Engineering

The following features were selected for training:

* BHK
* Total Square Feet
* Bathrooms
* Balconies
* Encoded Location
* Encoded Area Type

 Target Variable

* Price

---

 📈 Exploratory Data Analysis

The dataset was analyzed using various visualization techniques.

Performed analyses include:

* Distribution plots
* Correlation Heatmap
* Boxplots
* Outlier Analysis
* Feature Relationships

 Example Visualizations

* Correlation Matrix
* Boxplot for Outlier Detection
* Price Distribution
* Feature Correlation Heatmap

> **Note:** Add your screenshots inside the `images/` folder and reference them here.

Example:

```markdown
![Correlation Heatmap](images/heatmap.png)

![Boxplot](images/boxplot.png)
```

---

 🤖 Machine Learning Models

The following regression algorithms were implemented:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. K-Nearest Neighbors (KNN) Regressor
5. Support Vector Regressor (SVR)

---

 ⚖️ Feature Scaling

StandardScaler was applied to normalize numerical features before training models that are sensitive to feature scales.

---

 📏 Model Evaluation

The models were evaluated using:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)

---

🏆 Results

Replace the values below with your actual results.

| Model             | R² Score | MAE | MSE |
| ----------------- | -------: | --: | --: |
| Linear Regression |       XX |  XX |  XX |
| Decision Tree     |       XX |  XX |  XX |
| Random Forest     |       XX |  XX |  XX |
| KNN               |       XX |  XX |  XX |
| SVR               |       XX |  XX |  XX |

 Best Model

> **Random Forest Regressor** achieved the best performance based on the evaluation metrics and was selected as the final prediction model.

*(Update this section if another model performs better.)*

---

 🔄 Machine Learning Workflow

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

 📁 Project Structure

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

 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/House-Price-Prediction.git
```

Navigate to the project folder:

```bash
cd House-Price-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

 ▶️ Usage

1. Open the notebook.
2. Load the dataset.
3. Execute each notebook cell in sequence.
4. Train the regression models.
5. Compare evaluation metrics.
6. Use the best-performing model for prediction.

---

 📚 Python Libraries

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

 💡 Key Learnings

Through this project, I gained practical experience in:

* Data Cleaning
* Missing Value Handling
* Feature Engineering
* Exploratory Data Analysis
* Outlier Detection
* Feature Scaling
* Regression Algorithms
* Model Evaluation
* Machine Learning Pipeline Development

---

 🚀 Future Improvements

* Hyperparameter tuning using GridSearchCV.
* Implement XGBoost and LightGBM.
* Deploy the model using Flask or FastAPI.
* Build an interactive web application using Streamlit.
* Containerize the application using Docker.
* Add model explainability using SHAP or LIME.
* Automate model retraining with CI/CD pipelines.

---

 👨‍💻 Author

Sathish Reddy Manne

Aspiring Data Scientist | Machine Learning Enthusiast | AI & ML Student

* GitHub: https://github.com/yourusername
* LinkedIn: https://linkedin.com/in/yourprofile

---

 🙏 Acknowledgements

* Scikit-learn Documentation
* Pandas Documentation
* NumPy Documentation
* Matplotlib Documentation
* Seaborn Documentation

Special thanks to the open-source community for providing the tools and libraries used in this project.

---

 ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub. It helps others discover the project and motivates future improvements.
