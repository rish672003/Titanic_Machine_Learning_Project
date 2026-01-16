Titanic: Machine Learning from Disaster
This repository contains a comprehensive exploratory data analysis (EDA) and feature engineering pipeline for the classic Titanic survival prediction challenge. The goal is to predict which passengers survived the Titanic shipwreck using various machine learning models.

🚀 Project Overview
The project follows a standard data science workflow:

Data Loading: Importing the Titanic dataset.

Exploratory Data Analysis (EDA): Analyzing relationships between features (Class, Sex, Family Size) and survival rates.

Feature Engineering: * Title Extraction: Extracting social titles (Mr, Mrs, Miss, etc.) from passenger names.

Family Size Grouping: Combining SibSp and Parch to categorize passengers as Alone, Small, Medium, or Large families.

Age & Fare Binning: Using pd.qcut to create categorical bins for continuous variables.

Preprocessing: Handling missing values and encoding categorical data for model readiness.

📊 Key Insights from EDA
Social Status: Passengers in Pclass 1 had a significantly higher survival rate (~63%) compared to Pclass 3 (~24%).

Gender: Female passengers had a much higher survival rate (~74%) than male passengers (~19%).

Family Size: People traveling in "Small" families (2-4 members) had the highest survival probability (~58%).

Embarkation: Passengers who embarked from Cherbourg (C) showed higher survival rates compared to other ports.

🛠️ Built With
Python: The core programming language.

Pandas & NumPy: For data manipulation and numerical analysis.

Seaborn & Matplotlib: For data visualization.

Scikit-Learn: For preprocessing pipelines and machine learning algorithms (Logistic Regression, Random Forest, SVC, etc.).

📂 Project Structure
1.ipynb: The main Jupyter Notebook containing all the analysis and feature engineering code.

train.csv: Training data with survival labels.

test.csv: Test data for making predictions.

⚙️ How to Run
Clone the repository:

Bash
git clone https://github.com/your-username/titanic-survival-prediction.git
Install dependencies:

Bash
pip install pandas numpy seaborn matplotlib scikit-learn
Open 1.ipynb in Jupyter Notebook or VS Code to view the analysis.

📝 Future Work
Implement the final Machine Learning models (Random Forest, SVC, XGBoost).

Perform Hyperparameter Tuning using GridSearchCV.

Submit predictions to the Kaggle competition leaderboard.
