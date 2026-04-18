# CrimeInUS

This project analyzes whether a U.S. homicide case was solved using victim, perpetrator, and case characteristics from 1980–2014. It applies logistic regression for both classification performance and statistical interpretation.

## Files
- `CrimeInUS.ipynb` — main analysis notebook
- `practice.ipynb` — practice notebook used to learn the logistic regression workflow
- `README.md` — project description

## Methods
The analysis includes:
- data cleaning
- handling coded/impossible age values
- dummy coding categorical predictors
- logistic regression with scikit-learn for classification
- logistic regression with statsmodels for coefficient, odds ratio, and confidence interval interpretation

## Main Variables
- Crime Solved
- Victim Age
- Victim Sex
- Victim Race
- Perpetrator Age
- Perpetrator Sex
- Perpetrator Race
- Weapon
- Relationship
- Year

## Notes
Some placeholder or implausible age values were identified and treated during data cleaning before modeling.