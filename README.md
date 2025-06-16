# 🚢 Titanic Survival Analysis – Mini Project

This project analyzes the Titanic dataset from Kaggle to uncover the factors that affected passenger survival. It's an exploratory data analysis (EDA) project where I cleaned the data, visualized patterns, and extracted meaningful insights using Python, Pandas, Seaborn, and Matplotlib.

---

## 📌 Objective

To perform data analysis and gain insight into the survival patterns of passengers aboard the Titanic using visual exploration, feature analysis, and intuitive statistics.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Dataset

Dataset used: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)

The dataset includes passenger details such as age, sex, class, fare paid, and whether they survived or not.

---

## 📊 Key Steps

### 1. Data Cleaning
- Handled missing values in `Age`, `Embarked`, and `Cabin`
- Dropped or transformed unnecessary columns
- Created new features such as `FamilySize`

### 2. Data Visualization
Explored survival patterns using the following plots:
- Survival by Gender
- Survival by Passenger Class
- Survival Rate vs. Age Distribution
- Family Size vs. Survival
- Correlation Heatmap

### 3. Insights Extracted
- **Females had significantly higher survival rates** than males
- **1st class passengers** had the highest chance of survival
- Children and people with **smaller families** had better odds of surviving
- **Age** showed a survival dip for middle-aged men

---

## 📷 Screenshots

> Below are some screenshots of the analysis done in the notebook:

### 🎨 Survival by Gender
![Survival by Gender](screenshots/gender_survival.png)

### 📈 Age Distribution by Survival
![Age Distribution](screenshots/age_survival.png)

### 🧱 Correlation Heatmap
![Correlation Heatmap](screenshots/correlation.png)


---

## 🧠 Conclusion

This project helped build my skills in:
- Cleaning and preparing real-world data
- Visualizing data to extract patterns
- Asking the right questions to explore data
- Documenting my analysis in a clear, readable format

---

## 📌 How to Run

1. Clone this repo
2. Install dependencies:  
```bash
pip install pandas matplotlib seaborn
