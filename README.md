# tayyab415-Elevate-Labs-Day5

# **Titanic Survival Analysis**

This repository contains a Jupyter Notebook-based data analysis project focused on the Titanic dataset. The goal was to explore and identify the factors that influenced passenger survival in the 1912 disaster using data visualization and basic statistical techniques.

---

## Repository Contents

| File Name               | Description |
|-------------------------|-------------|
| `day-5.ipynb`           | Jupyter Notebook performing data cleaning, exploration, and survival analysis |
| `Titanic_Analysis_Report.pdf` | PDF report summarizing key findings and insights from the analysis |
| `train.csv`             | Titanic dataset containing demographic and ticket data for training (source: Kaggle) |

---

## Problem Statement

> Analyze passenger demographics and ticket/class data from the Titanic dataset to uncover what influenced survival outcomes during the disaster. Focus on the impact of gender, passenger class, age, and fare on survival probabilities.

---

## Dataset Description

The dataset used (`train.csv`) contains:
- PassengerId
- Survived (target variable: 0 = No, 1 = Yes)
- Pclass (Ticket class: 1 = First, 2 = Second, 3 = Third)
- Name, Sex, Age
- SibSp, Parch (family onboard)
- Ticket, Fare
- Cabin, Embarked (port of embarkation)

---

## Key Procedures in `day-5.ipynb`

- Data loading and preview
- Handling missing values (especially in Age and Embarked)
- Feature exploration (Age, Sex, Pclass, Fare)
- Visualization using Seaborn and Matplotlib
- Grouped statistics by survival and gender/class
- Correlation checks (Survival vs. other features)

---

## Summary of Key Findings

As outlined in `Titanic_Analysis_Report.pdf`:

### Demographics
- Most passengers were aged 20–40
- Male passengers outnumbered female passengers
- Majority of travelers were in third class

### Survival Analysis
- Women had a much higher survival rate (~75%) than men (<20%)
- First-class passengers had the highest survival chances
- Third-class passengers had the lowest survival rate

### Economic Influence
- Higher fares correlated with better survival odds
- First-class tickets were significantly more expensive and variable in price
- Third-class passengers consistently paid the least and had poor survival outcomes

### Key Correlations
- Survival strongly correlated with gender and class
- Age was not a strong standalone predictor
- Socioeconomic status (via fare and class) clearly influenced survival outcomes

---

## Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Usage

To reproduce this analysis:
1. Clone the repository
2. Open `day-5.ipynb` in Jupyter Notebook
3. Make sure `train.csv` is in the same directory
4. Run the notebook cells to view visualizations and findings

---

## Conclusion

This project highlights the historical social inequalities present during the Titanic tragedy. Gender and class had the most significant impact on survival, with women and first-class passengers having the highest probability of survival.

For more detailed insights, refer to the `Titanic_Analysis_Report.pdf` file.

---
