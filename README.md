# 🏥 Medical Insurance Cost Prediction

## 📌 Project Overview

This project focuses on predicting individual medical insurance costs using Machine Learning regression algorithms.

The main objective is to understand how factors such as age, BMI, smoking status, gender, number of children, and residential region relate to medical insurance charges.

Three regression models are implemented and evaluated:
- Linear Regression
- Lasso Regression
- Ridge Regression

## 🎯 Project Objectives

- Explore and understand the medical insurance dataset.
- Perform data cleaning and preprocessing.
- Analyze relationships between features and insurance charges.
- Train multiple regression models.
- Evaluate and compare model performance.

## 📂 Dataset Information

The dataset contains **1,338 records and 7 columns** before cleaning.

| Column | Description |
|---|---|
| age | Individual's age |
| sex | Gender |
| bmi | Body Mass Index |
| children | Number of children |
| smoker | Smoking status |
| region | Residential region |
| charges | Medical insurance cost (Target Variable) |

After removing duplicate records, the dataset contains **1,337 records**.

## 🛠️ Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔍 Project Workflow

### 1. Data Loading
- Imported the dataset using Pandas.
- Explored the dataset using `head()`, `tail()`, `shape`, and `info()`.

### 2. Data Cleaning
- Checked missing values.
- Identified duplicate records.
- Removed duplicate records.

### 3. Exploratory Data Analysis (EDA)

Created visualizations to understand:
- Smoker vs Insurance Charges
- BMI vs Insurance Charges
- Age vs Insurance Charges
- Distribution of Insurance Charges
- Region-wise Average Charges
- Children vs Insurance Charges

### 4. Data Preprocessing
- Encoded categorical variables.
- Separated independent and dependent variables.
- Applied StandardScaler for feature scaling.

### 5. Train-Test Split

Split the dataset into:
- 80% Training Data
- 20% Testing Data

Used `random_state=42` for reproducibility.

### 6. Model Building

Implemented three regression algorithms:

1. Linear Regression
2. Lasso Regression
3. Ridge Regression

### 7. Model Evaluation

Evaluated model performance using:

- R² Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## 📊 Model Performance

Results from the current notebook:

| Model | R² Score | RMSE |
|---|---:|---:|
| Linear Regression | 0.8068 | 5957.61 |
| Lasso Regression | 0.8068 | 5958.16 |
| Ridge Regression | 0.8067 | 5960.44 |

**Best Performing Model:** Linear Regression

The Linear Regression model achieved an R² score of approximately 0.807 on the test dataset.

## 📁 Project Structure

```text
Medical-Insurance-Cost-Prediction/
│
├── Medical_Insurance_Cost_Prediction.ipynb
├── insurance.csv
└── README.md
```

## 🚀 How to Run This Project

1. Clone this repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

2. Navigate to the project folder:

```bash
cd Medical-Insurance-Cost-Prediction
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

4. Make sure `insurance.csv` is in the project folder.

5. Launch Jupyter Notebook:

```bash
jupyter notebook
```

6. Open `Medical_Insurance_Cost_Prediction.ipynb` and run the cells.

## 💡 Future Improvements

- Apply One-Hot Encoding for the region feature.
- Experiment with additional regression algorithms.
- Perform hyperparameter tuning.
- Compare models using MAE, MSE, RMSE, and R² Score.
- Improve prediction performance through feature engineering.

## 👨‍💻 Author

**Koushik Tirgar**

Aspiring Data Scientist | BCA Student | Machine Learning Enthusiast

Interested in Data Analytics, Machine Learning, and solving real-world problems using data.

---

⭐ If you find this project useful, feel free to explore the repository!
