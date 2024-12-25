# Data-Cleaning-and-EDA
# Titanic Data Cleaning and EDA Project

## Project Overview
This project focuses on cleaning and analyzing the Titanic dataset to uncover insights about passenger survival. The primary goal is to understand the factors influencing survival rates using data cleaning techniques and exploratory data analysis (EDA).

---

## Dataset Used
- **Name:** Titanic Dataset
- **Source:** [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data)
- **Description:** The dataset provides details about Titanic passengers, including demographics and survival information.

---

## Steps Performed
1. **Data Loading and Exploration**:
   - Overview of the dataset.
   - Identification of missing values.

2. **Data Cleaning**:
   - Removed unnecessary columns (`PassengerId`, `Name`, `Ticket`, `Cabin`).
   - Handled missing values in `Age` and `Embarked`.
   - Encoded categorical variables (`Sex`, `Embarked`).

3. **Exploratory Data Analysis (EDA)**:
   - Visualized age distribution, survival counts, and correlations.
   - Analyzed survival trends by gender and passenger class.

4. **Saved Cleaned Dataset**:
   - Exported the cleaned dataset for future use.

---

## Key Insights
- **Gender and Survival**: Females had a significantly higher survival rate than males.
- **Class and Survival**: Passengers in first class were more likely to survive.
- **Age Distribution**: Younger passengers (children) had a higher survival rate.

---

## How to Run
1. Clone the repository or download the files.
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
