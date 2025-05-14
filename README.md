# Titanic Survival Prediction

This project aims to predict the survival of passengers on the **Titanic** using machine learning classification techniques. It is based on the famous Titanic dataset from [Kaggle](https://www.kaggle.com/competitions/titanic), which is a popular beginner-level data science competition.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Usage](#usage)
- [License](#license)

## Overview

In this notebook, we:

- Explore and analyze the dataset  
- Handle missing values  
- Perform feature engineering and encoding  
- Train classification models  
- Evaluate model performance  
- Make predictions on test data  

The goal is to determine which passengers are more likely to survive based on features like age, sex, ticket class, etc.

## Dataset

The dataset includes the following features:

- `Pclass`: Ticket class  
- `Sex`: Gender  
- `Age`: Age in years  
- `SibSp`: Number of siblings/spouses aboard  
- `Parch`: Number of parents/children aboard  
- `Fare`: Passenger fare  
- `Embarked`: Port of Embarkation  
- `Survived`: (Target) 0 = No, 1 = Yes

## Technologies Used

- Python 3  
- pandas  
- NumPy  
- scikit-learn  
- Matplotlib / Seaborn  

## Installation

1. Clone the repository:

```bash
git clone https://github.com/bakituncher/titanic.git
cd titanic
