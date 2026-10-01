# Titanic Dataset Exploratory Data Analysis (EDA)

## Objective

The objective of this project is to perform Exploratory Data Analysis (EDA) on the Titanic dataset, clean the data, create useful features, and identify patterns related to passenger survival.

## Dataset

Dataset used:
https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv

## Data Cleaning

- Missing Age values were replaced using the median age.
- Missing Embarked values were replaced using the mode.
- A CabinKnown feature was created to indicate whether cabin information was available.
- The original Cabin column was removed.
- FamilySize was created using SibSp + Parch + 1.
- IsAlone was created to identify passengers travelling alone.

## Visualizations

- Survival Rate by Passenger Class and Gender
- Age Distribution of Titanic Passengers
- Correlation Heatmap of Numerical Features

## Key Observations

1. Female passengers had a survival rate of 74.20%, compared with 18.89% for male passengers.
2. Passengers travelling in small family groups generally had higher survival rates than passengers travelling alone.
3. The average age of survivors was 28.29 years, compared with 30.03 years for non-survivors.

## Conclusion

The Titanic dataset shows clear differences in survival across gender and family size.
Female passengers had a substantially higher survival rate than male passengers.
Passengers travelling in small family groups generally showed better survival rates than those travelling alone.
The average ages of survivors and non-survivors were relatively similar.
