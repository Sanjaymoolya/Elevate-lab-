# Elevate-lab-
Task 1

🚢 Titanic Dataset - Data Cleaning & Preprocessing

📌 Objective
To clean and preprocess the Titanic dataset to prepare it for machine learning applications. This includes handling missing data, encoding categorical features, feature scaling, and outlier detection.

---

🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

🔍 Steps Performed

1. **Data Loading**
   - Loaded dataset into Pandas from a `.csv` file.

2. **Exploratory Data Analysis (EDA)**
   - Used `.head()`, `.info()`, `.isnull().sum()` to understand data structure and nulls.

3. **Missing Values**
   - Filled missing `Age` with median.
   - Imputed `Embarked` with mode.
   - Dropped `Cabin` due to excessive nulls.

4. **Encoding**
   - Encoded `Sex` and `Embarked` using Label Encoding or One-Hot Encoding.

5. **Feature Scaling**
   - Normalized `Age`, `Fare` using `StandardScaler`.

6. **Outlier Detection**
   - Used `boxplot()` to identify and remove outliers from `Fare` and `Age`.

---

📂 Dataset
- Titanic Dataset CSV:  
  [🔗 Download Titanic Dataset](https://www.kaggle.com/datasets/brendan45774/titanic-machine-learning-from-disaster)


🚀 How to Run
- Upload the Titanic dataset (`titanic.csv`) in Colab or Jupyter.
- Open and run the notebook `titanic_cleaning.ipynb`.


## 🎯 What I Learned
- Cleaning real-world datasets
- Dealing with missing/null values
- Encoding categorical data
- Feature scaling & outlier visualization

---

## 👨‍💻 Author
Sanjay Moolya

