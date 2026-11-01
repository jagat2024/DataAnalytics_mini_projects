# 🚗 Ford Car Price Prediction | Machine Learning

A Machine Learning project focused on analyzing Ford used-car data and predicting car prices using **Linear Regression**.

## 🎯 Project Overview

This project covers Exploratory Data Analysis (EDA), data preprocessing, feature encoding, feature scaling, and regression model development.

It also compares **One-Hot Encoding vs Label Encoding** to understand their impact on model performance.

## 📊 Dataset

- **Dataset:** Ford Car Price Prediction (`ford.csv`)
- **Records:** 17,966
- **Features:** 8 independent variables
- **Target:** `price`
- **Columns:** model, year, price, transmission, mileage, fuelType, tax, mpg, engineSize

## 🔍 Exploratory Data Analysis

Performed EDA using Pandas, Matplotlib and Seaborn.

- Dataset structure and statistical analysis
- Missing-value inspection
- Price distribution analysis
- Correlation heatmap
- Scatterplots and boxplots
- Feature-wise price comparisons

## ⚙️ Data Preprocessing

- Separated independent and dependent variables.
- Checked missing values.
- Applied **One-Hot Encoding** using `pd.get_dummies()`.
- Applied **Label Encoding** using `LabelEncoder`.
- Scaled numerical features using `StandardScaler`.
- Split data into training and testing sets (67:33).

## 🤖 Model Development

**Algorithm:** Linear Regression

- Trained separate models using One-Hot and Label Encoding workflows.
- Generated predictions on test data.
- Evaluated performance using R² and Adjusted R².

## 📈 Model Performance

| Encoding Technique | R² Score | Adjusted R² |
|---|---:|---:|
| One-Hot Encoding | 0.8402 | 0.8393 |
| Label Encoding | 0.7310 | 0.7307 |

**Winner: One-Hot Encoding 🏆**

The One-Hot Encoding workflow achieved better performance in this experiment.

## 🛠️ Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 💡 Key Learnings

- Understanding real-world datasets through EDA.
- Handling categorical variables.
- Feature scaling and preprocessing.
- Building regression models.
- Evaluating and comparing ML model performance.

## 🚀 Future Improvements

- Prevent data leakage using Scikit-learn Pipelines.
- Perform advanced feature engineering.
- Experiment with Ridge and Lasso Regression.
- Explore Random Forest and other regression algorithms.
- Evaluate using MAE, MSE and RMSE.
- Apply cross-validation and hyperparameter tuning.

## 📁 Project Structure

```text
Ford-Car-Price-Prediction/
│
├── Ford_car_analysis.ipynb
├── ford.csv
└── README.md
```

## 👨‍💻 Author

**Jagat Prasanna Shaw**

Interested in Machine Learning, AI and Software Development.

---

⭐ If you find this project interesting, feel free to explore the notebook!
