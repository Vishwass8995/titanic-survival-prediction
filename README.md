# 🚢 Titanic Survival Prediction

A Machine Learning project to predict passenger survival on the Titanic
using classification algorithms.

## 📊 Results
| Model | Accuracy |
|---|---|
| Logistic Regression | 79.89% |
| Random Forest | **82.68%** ✅ Best |

## 🔍 Key Insights Discovered
- **Sex** was the #1 survival factor (females survived at 74.2% vs males 18.9%)
- **1st class passengers** survived at 63% vs 3rd class at only 24.2%
- **Small families (2–4)** survived more than solo travelers or large groups
- A 1st class female aged 28 has a **97% survival probability**

## 🛠️ Tech Stack
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📁 Project Steps
1. Data Loading & Exploration (EDA)
2. Data Cleaning (handled missing values)
3. Feature Engineering (FamilySize, IsAlone, AgeGroup, FareGroup)
4. Model Building (Logistic Regression + Random Forest)
5. Model Evaluation (Confusion Matrix, Classification Report)

## 📂 Dataset
[Titanic Dataset](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

## 👤 Author
**Vishwas Sharma** — Aspiring Data Scientist
