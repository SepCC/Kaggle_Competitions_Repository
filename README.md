# 🏆 Kaggle Competitions Playground

Welcome to my Kaggle repository! This is a monorepo containing my end-to-end machine learning solutions for various Kaggle competitions. 

I focus on robust data preprocessing, extensive feature engineering, rigorous hyperparameter tuning, and avoiding data leakage.

## 📁 Completed Competitions

| Competition | Task | Model | Local CV Score | Code Link |
| :--- | :--- | :--- | :--- | :--- |
| **[House Prices - Advanced Regression](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)** | Regression | XGBoost | **0.11095** (RMSE) | [View Code](./01_House_Prices/) |

*(More competitions like Titanic and Digit Recognizer will be added soon...)*

## 🛠️ Tech Stack & Tools
- **Languages**: Python 3
- **Data Manipulation**: Pandas, NumPy
- **Machine Learning**: Scikit-Learn, XGBoost
- **Data Visualization**: Matplotlib, Seaborn
- **Environment**: Kaggle Notebooks, Jupyter

## 📂 Repository Structure
```text
Kaggle_Competitions_Repository/
│
├── 01_House_Prices/            # Ames Housing Dataset
│   ├── README.md               # Project-specific documentation
│   ├── house_prices_xgb.ipynb  # Complete EDA, Feature Eng, and Modeling
│   ├── requirements.txt        # Dependencies for this project
│   └── outputs/                # Final submission files
│
├── .gitignore                  # Global ignore (protects from uploading large CSVs)
└── README.md                   # This file
