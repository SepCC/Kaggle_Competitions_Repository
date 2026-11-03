# House Prices - Advanced Regression Techniques (Kaggle)

This repository contains my end-to-end machine learning solution for the Kaggle Ames Housing dataset.

## 🏆 Results
- **Model**: XGBoost Regressor
- **Validation Strategy**: 5-Fold Cross Validation (CV)
- **Final CV RMSE**: `0.11095` (aligned with official RMSLE metric)

## 🚀 Project Workflow
1. **Exploratory Data Analysis (EDA)**: Analyzed `SalePrice` distribution, applied `log1p` transformation to align with RMSLE.
2. **Data Preprocessing**: Handled missing values based on domain knowledge (e.g., NaN in garage columns means "No Garage"). Used Ordinal and One-Hot encoding.
3. **Feature Engineering**: Created composite features like `TotalSF` (Total Square Feet), `TotalBath`, and `HouseAge`, which significantly improved model performance.
4. **Outlier Removal**: Dropped extreme outliers (e.g., `GrLivArea > 4000` but cheap price).
5. **Model Tuning**: Conducted a rigorous 5-stage grid search (tuning `n_estimators`, tree structure, subsampling, learning rate, and regularization parameters) to prevent overfitting and optimize CV score.

## 📁 Repository Structure
- `notebooks/`: Contains the complete Jupyter Notebook.
- `outputs/`: Contains the final `submission.csv` file.
- `requirements.txt`: Python dependencies.

## 🛠️ Built With
- Python 3.11, Pandas, NumPy, Scikit-Learn, XGBoost, Matplotlib, Seaborn