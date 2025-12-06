# HexSoftwares_Project1_EDA
Exploratory Data Analysis (EDA) Project for HexSoftwares Internship. Includes data cleaning, visualization, and insights.
This repository contains my Project 1 as a Data science Intern at HexSoftwares.
The project focuses on performing Exploratory Data Analysis (EDA) on a public dataset using Python

Dataset name: Titanic-Dataset
Source: Kaggle
Dataset link: [paste the link here](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

Tools & Technologies

Python (Pandas, Matplotlib, Seaborn), Jupyter Notebook

🔹 Project Steps

1. Data Loading

✔ Loaded the dataset into pandas dataframe

✔ Displayed first few rows

 2. Data Cleaning

✔ Checked for missing values

✔ Handled missing values (fill/drop)

✔ Removed duplicates

 3. Statistical Analysis

✔ .info()

✔ .describe()

  4. Exploratory Data Analysis (EDA)

✔ Distribution plots

✔ Countplots

✔ Correlation heatmap

✔ Boxplots.



This section provides key insights from the exploratory data analysis (EDA) conducted on the Titanic dataset. The goal is to identify patterns that influenced passenger survival, and understand how demographic, socio-economic, and travel-related variables impacted outcomes.

1. Gender Played a Major Role in Survival

A clear pattern emerges when examining early entries and the full dataset:

Most females survived, while

Most males did not.

This reflects the evacuation rule of the time:
“Women and children first.”

🔍 Insight:

Gender was one of the strongest predictors of survival.
Females had a significantly higher survival rate than males.

2. Passenger Class Strongly Influenced Outcome

The dataset shows a sharp contrast between:

1st-class passengers, who often survived

3rd-class passengers, who mostly died

Higher-class passengers were physically closer to the lifeboats and received prioritized assistance.

🔍 Insight:

Passenger class (Pclass) is a strong socio-economic indicator.
First-class passengers enjoyed a much higher chance of survival than third-class passengers.

3. Wealth and Fare Amount Linked to Survival

A quick comparison of fare values reveals:

Survivors often paid higher fares, reflecting greater wealth.

Passengers with low fares—typically in 3rd class—had lower survival rates.

🔍 Insight:

Higher fares correlated with higher survival.
Wealthier passengers had greater access to safer locations on the ship.

4. Family Size Influenced Survival Patterns

Family size is represented by:

SibSp (siblings/spouses aboard)

Parch (parents/children aboard)

Observations show:

Some passengers traveling with family had better survival outcomes.

Those traveling alone may have had less support during evacuation.

🔍 Insight:

Family presence may have contributed to survival, though its effect is moderate compared to sex and class.

5. Cabin Information Indicates Socioeconomic Status

Cabin data is highly incomplete:

Many passengers, especially 3rd class, have no cabin number.

Most cabins that appear in the dataset belong to 1st-class passengers.

🔍 Insight:

Having a cabin number generally indicates higher status and a better chance of survival.

6. Embarkation Port Shows Social Differences

Passengers boarded from three ports:

S (Southampton)

C (Cherbourg)

Q (Queenstown)

Notable patterns:

Many wealthy passengers boarded at Cherbourg, contributing to their higher survival rates.

Most 3rd-class passengers boarded at Southampton, where survival was lower.

Final Insight:

Survival on the Titanic was determined by a combination of social privilege (class, wealth), demographic characteristics (sex, age), and access to lifeboats.
🔍 Insight:

Embarked location reflects socio-economic grouping, indirectly affecting survival.
