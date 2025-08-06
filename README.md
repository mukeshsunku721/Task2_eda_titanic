# 📊 Task 2: Exploratory Data Analysis (EDA) – Titanic Dataset

This notebook explores the Titanic dataset through summary statistics and visualizations to better understand the data, detect patterns, and identify potential modeling issues.

---

##  Objective

- Perform Exploratory Data Analysis (EDA)
- Visualize relationships between features
- Detect outliers, skewness, and missing values
- Draw preliminary conclusions to guide model design

---

##  Tools Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Plotly (optional)

---

##  Dataset

- Dataset used: [Titanic Dataset – Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- Target variable: `Survived` (0 = No, 1 = Yes)

---

## 🔍 Steps Performed

### 1. 📋 Summary Statistics
- Used `.describe()` and `.info()` to get:
  - Mean, median, standard deviation
  - Null values and data types

### 2. 📈 Univariate Analysis
- **Histograms** to understand distribution of:
  - `Age`, `Fare`, `SibSp`, `Parch`
- **Boxplots** to detect outliers in:
  - `Age` and `Fare`

### 3. 🔗 Bivariate/Multivariate Analysis
- **Correlation heatmap** to observe linear relationships
- **Pairplot** to study feature interactions grouped by `Survived`
- **Count plots** for categorical features vs survival:
  - `Pclass`, `Sex`, `Embarked`

### 4. 📊 Key Visual Tools
- Seaborn plots: `histplot`, `boxplot`, `countplot`, `pairplot`
- Matplotlib for basic plots
- Optional: Plotly for interactive charts

---

## 🧠 Insights & Observations

- **Females** had a higher survival rate than males
- Passengers in **1st class** survived more often than those in 2nd or 3rd
- **Fare and Age** showed a right-skewed distribution
- **Outliers** detected in `Fare` (extremely high values)
- Port **Embarked='C'** showed higher survival rate

---

## 📦 How to Run

```bash
pip install pandas numpy matplotlib seaborn plotly
