
# 🚢 Task 1: Titanic Data Cleaning & Preprocessing

This project is part of the AI/ML Internship Program, where I focused on building a strong foundation in data cleaning and preprocessing — a crucial step in any machine learning pipeline. The dataset used is the famous Titanic dataset from Kaggle.

---

## 🎯 Objective

To clean and prepare the Titanic dataset by handling missing values, encoding categorical variables, scaling features, and detecting/removing outliers — making it ready for machine learning models.

---

## 📂 Dataset

- Source: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File used: `Titanic-Dataset.csv`

---

## 🧹 Data Cleaning Steps

- ✅ Identified missing values using `df.isnull().sum()`
- ✅ Filled missing values in `Age` using median
- ✅ Filled missing values in `Embarked` using mode
- ✅ Dropped the `Cabin` column due to high missingness

---

## 🔁 Data Preprocessing

- 🧠 Applied One-Hot Encoding to `Sex` and `Embarked`
- 📏 Standardized `Age` and `Fare` using `StandardScaler`
- 📊 Visualized outliers with boxplots (Seaborn)
- ❌ Removed outliers using the IQR method

---

## 🛠️ Tech Stack

- Python 3.x
- Jupyter Notebook
- Libraries:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `scikit-learn`

---

## 📁 Files Included

| File Name                      | Description                           |
|-------------------------------|---------------------------------------|
| `Titanic-Dataset.csv`         | Raw Titanic dataset                   |
| `Titanic_Data_Cleaning.ipynb` | Jupyter Notebook with code & outputs  |
| `Cleaned_Titanic.csv`         | Final cleaned dataset                 |
| `README.md`                   | This documentation                    |

---

## 🧪 How to Run

```bash
# Step 1: Clone this repository
git clone https://github.com/your-username/task-1-titanic-cleaning.git

# Step 2: Open the folder
cd task-1-titanic-cleaning

# Step 3: Run Jupyter Notebook
jupyter notebook Titanic_Data_Cleaning.ipynb
```

> 💡 Alternatively, open the notebook in [Google Colab](https://colab.research.google.com/) or VS Code.

---

## 💼 Internship Relevance

This task mirrors real-world data preprocessing tasks performed by data analysts and ML engineers. It reflects attention to detail, pipeline structuring, and data integrity practices.

---

## 🚀 Submission

Final output was uploaded to GitHub and submitted through the official internship portal.

---

**Impress recruiters by mastering the foundations. Clean data builds smart models.** ✨
