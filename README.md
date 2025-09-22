AI & ML Internship – Task 1: Data Cleaning & Preprocessing
📌 Objective

Learn how to clean and prepare raw data for Machine Learning models by handling missing values, encoding categorical variables, scaling features, and removing outliers.

📂 Dataset

Dataset used: Titanic Dataset

Source: Kaggle Titanic Dataset

File: titanic.csv

🔧 Steps Performed
1. Import & Explore Data

Loaded dataset using Pandas

Checked data types, shape, and missing values

2. Handle Missing Values

Numerical: Filled with median (e.g., Age)

Categorical: Filled with mode (e.g., Embarked)

3. Encode Categorical Variables

Used Label Encoding for Sex

Used One-Hot Encoding for Embarked

4. Normalize / Standardize Features

Applied StandardScaler on Age and Fare

5. Outlier Detection & Removal

Used Boxplots to visualize outliers

Removed extreme values using IQR method

📊 Visualizations

Missing values heatmap

Boxplots for outlier detection

Histograms for feature distribution

(Add screenshots here if you took them, e.g. images/boxplot.png)

📝 Interview Prep (Quick Answers)

Types of Missing Data → MCAR, MAR, MNAR

Handle Categorical Variables → Label Encoding, One-Hot Encoding

Normalization vs Standardization → Normalization: scale [0–1], Standardization: mean=0, std=1

Detect Outliers → Boxplots, Z-score, IQR method

Why Preprocessing? → Improves quality, reduces noise, boosts accuracy

One-Hot vs Label Encoding → One-Hot = binary columns, Label = integer values

Handle Data Imbalance → SMOTE, undersampling, class weights

Does Preprocessing Affect Accuracy? → ✅ Yes, crucial for better performance

📁 Repository Structure
AI-ML-Internship-Task1/
│
├── task1_preprocessing.ipynb   # Jupyter Notebook with code
├── titanic.csv                 # Dataset
├── images/                     # Screenshots/plots (optional)
└── README.md                   # Documentation

🚀 Tools & Libraries Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

✅ How to Run

Clone the repo

git clone https://github.com/yourusername/AI-ML-Internship-Task1.git
cd AI-ML-Internship-Task1


Open Jupyter Notebook

jupyter notebook task1_preprocessing.ipynb
