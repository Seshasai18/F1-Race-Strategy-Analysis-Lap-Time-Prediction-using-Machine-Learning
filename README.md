# F1-Race-Strategy-Analysis-Lap-Time-Prediction-using-Machine-Learning
Problem Statement  Formula 1 performance depends heavily on race strategy, tyre management, and lap consistency. This project aims to:  Analyze race data Identify key factors affecting lap time Build ML models to predict lap times

F1-Race-Strategy-Analysis/
│
├── data/
│   └── f1_strategy_dataset_v2.csv
│
├── notebooks/
│   └── F1.ipynb
│
├── src/ (optional but strong)
│   └── model.py
│
├── images/ (plots/screenshots)
│
├── requirements.txt
├── README.md
└── .gitignore

Dataset
Source: kaggle
Features include:
Driver
Lap Number
Tyre Compound
Tyre Life
Position
Race / Year
Lap Time (target)

Project Workflow
Step 1: Data Preprocessing
Missing value handling
Feature inspection
Basic cleaning
Step 2: Exploratory Data Analysis (EDA)
Distribution of lap times
Tyre impact analysis
Driver performance trends
Step 3: Feature Engineering
Encoding categorical variables
Handling skewed data


Step 4: Model Building
I likely used:
Linear Regression
Decision Tree
Random Forest
SVM

Step 5: Evaluation
Metrics used: RMSE, MAE, R² Score


Tech Stack:Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn


