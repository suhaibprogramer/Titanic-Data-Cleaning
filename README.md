# 🚢 Titanic Data Cleaning Project

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.x-green?logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Complete-success)

---

## 📌 Project Overview

This is my **first data cleaning project** completed as part of the **Data Analytics Training Program**.

I worked with the Titanic dataset to identify and fix data quality issues, making it clean and ready for analysis.

---

## 🎯 Project Objective

The goal was to:
- ✅ Import and explore the Titanic dataset
- ✅ Identify missing values and data quality issues
- ✅ Apply appropriate cleaning techniques
- ✅ Verify and correct data types
- ✅ Rename columns for better readability
- ✅ Save the final cleaned dataset

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Python** | Programming language |
| **Pandas** | Data manipulation and cleaning |
| **Google Colab** | Jupyter Notebook environment |
| **GitHub** | Version control and project hosting |

---

## 📊 About the Dataset

- **Source:** Kaggle Titanic Dataset
- **Original Rows:** 891
- **Original Columns:** 12
- **Target Variable:** Survived (0 = No, 1 = Yes)

---

## 🔧 Data Cleaning Steps Performed

### 1️⃣ Identified Data Quality Issues

| Column | Issue | Count |
|--------|-------|-------|
| Age | Missing values | 177 |
| Cabin | Missing values | 687 |
| Embarked | Missing values | 2 |
| Duplicates | None found | 0 |

### 2️⃣ Handled Missing Values

| Column | Solution |
|--------|----------|
| **Age** | Filled with median age (28 years) |
| **Cabin** | Filled with 'Unknown' |
| **Embarked** | Filled with mode ('S' - Southampton) |

### 3️⃣ Corrected Data Types

| Column | Before | After |
|--------|--------|-------|
| Age | float | integer |
| Sex | object | category |
| Survived | int | category |
| Pclass | int | category |

### 4️⃣ Renamed Columns for Clarity

| Original Name | New Name |
|---------------|----------|
| PassengerId | ID |
| SibSp | Family_Members |
| Parch | Parents_Children |

### 5️⃣ Final Validation

- ✅ No missing values remaining
- ✅ No duplicate rows
- ✅ Correct data types
- ✅ Clean and consistent dataset

---

## 📊 Key Findings from Cleaned Data

| Metric | Result |
|--------|--------|
| **Total Passengers** | 891 |
| **Survival Rate** | 38.4% (342 survived) |
| **Women Survival** | 74.2% (233 survived) |
| **Men Survival** | 18.9% (109 survived) |

### Survival by Gender

```
Women: ████████████████████████████████████ 74.2%
Men:   ██████████ 18.9%
```

### Survival by Passenger Class

| Class | Passengers | Survival Rate |
|-------|-----------|---------------|
| 1st Class | 216 | 63.0% |
| 2nd Class | 184 | 47.3% |
| 3rd Class | 491 | 24.2% |

```
1st Class: ████████████████████████████████ 63.0%
2nd Class: ████████████████████████ 47.3%
3rd Class: ████████████ 24.2%
```

---

## 📁 Repository Structure

```
Titanic-Data-Cleaning/
│
├── README.md                                    # Project documentation (this file)
├── LICENSE                                      # MIT License
├── Titanic_Dataset_–_Data_Preparation_&_Cleaning (1).ipynb  # Jupyter Notebook with code
└── cleaned_titanic.csv                          # Final cleaned dataset
```

---

## 🚀 How to Run This Project

### Option 1: Google Colab (Recommended)

1. Go to [Google Colab](https://colab.research.google.com/)
2. Upload the notebook file:
   - Click **File** → **Upload notebook**
   - Select `Titanic_Dataset_–_Data_Preparation_&_Cleaning (1).ipynb`
3. Run all cells:
   - Click **Runtime** → **Run all**

### Option 2: Local Jupyter Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/suhaibprogramer/Titanic-Data-Cleaning.git
   ```

2. Install required libraries:
   ```bash
   pip install pandas numpy
   ```

3. Navigate to the folder and open the notebook:
   ```bash
   jupyter notebook
   ```

---

## 📝 Assumptions Made

1. **Missing Age values** → Represent average passenger age (28 years)
2. **Missing Cabin values** → Passenger had no cabin assigned
3. **Missing Embarked values** → Most common port (Southampton)

---

## 📈 Future Work

- 📊 Perform exploratory data analysis (EDA)
- 🤖 Build predictive models for survival
- 📈 Create visualizations with matplotlib/seaborn
- 🔍 Feature engineering for better predictions

---

## 👤 Author

**suhaibprogramer**  
Data Analytics Trainee

- 📧 Email: [Add your email here]
- 🔗 GitHub: [suhaibprogramer](https://github.com/suhaibprogramer)
- 🔗 LinkedIn: [Add your LinkedIn here]

---

## 📅 Date

**July 2026**

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- [Kaggle](https://www.kaggle.com/) for providing the Titanic dataset
- Internee Data Analytics Training Program
- Open-source Python libraries (Pandas, NumPy)

---

## ⭐ Show Your Support

If you found this project helpful, please give it a ⭐ on GitHub!

---

**Made with ❤️ by suhaibprogramer**
