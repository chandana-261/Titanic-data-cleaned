# 🧼 Titanic Data Cleaning & Preprocessing
This project demonstrates a complete workflow for cleaning and preprocessing raw data from the Titanic dataset in preparation for machine learning. The task includes handling missing values, encoding categorical variables, removing outliers, normalizing features, and generating visualizations for insights.

## 📌 Objective
To learn and apply essential data preprocessing techniques using Python libraries like Pandas, NumPy, Seaborn, Matplotlib, and Scikit-learn.

## 📂 Dataset
The dataset used is the famous [Titanic dataset](https://www.kaggle.com/competitions/titanic/data) which includes information about passengers such as:
- Age, Sex, Fare, Passenger Class
- Survival status
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Embarkation point

## 🧰 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## 🔧 Preprocessing Steps
1. Import and Explore the Dataset
- Loaded dataset using Pandas.
- Explored structure and identified missing values.

2. Handle Missing Values
- Filled missing values in `Age` with the **median**.
- Filled missing values in `Embarked` with the **mode**.
- Dropped `Cabin` (highly sparse), `Name`, `Ticket`, and `PassengerId`.

3. Encode Categorical Variables
- Converted `Sex` to numeric (male → 0, female → 1).
- Applied **One-Hot Encoding** to `Embarked`.

 4. Outlier Detection and Removal
- Visualized `Age` and `Fare` distributions using boxplots.
- Removed outliers using the **Interquartile Range (IQR)** method.

 5. Normalize Numerical Features
- Standardized `Age`, `Fare`, `SibSp`, and `Parch` using **StandardScaler**.

## 📊 Visualizations
- Survival Count
- Survival by Sex
- Survival by Passenger Class
- Correlation Heatmap
These help identify trends such as higher survival rates among females and first-class passengers.

## 💾 Output
- Cleaned dataset saved as: `Titanic_Cleaned.csv`
- Notebook saved in: `Titanic_Data_Cleaning.ipynb`

## 🚀 How to Run
1. Open `Titanic_Data_Cleaning.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter.
2. Run all cells to perform preprocessing and generate visualizations.
3. Explore the cleaned dataset or continue with model training.

## 📌 License
This project is open-source and available under the [MIT License](LICENSE).

## ✍️ Author

**Chandana**  
_Data Science Enthusiast | Machine Learning Learner_

Feel free to fork, star ⭐ the repo, or raise issues/PRs!
