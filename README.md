
# AI Salary Prediction

This project aims to build and compare machine learning models to **predict employee salaries** based on various job-related and demographic features.
It also explores **which factors influence salary the most** and **which skills are in highest demand**.

## Objective

* Predict `salary_usd` using structured job market data
* Perform **EDA**, **Feature Engineering**, and **Model Comparison**
* Identify most influential features and valuable skills

## Project Structure

```
├── 01-EDA.ipynb             # Exploratory Data Analysis
├── 02-Feature-Engineering.ipynb
├── 03-Model-Training.ipynb  # Model pipelines & tuning
├── data/
│   ├── raw_data/
│   ├── processed_data/
└── README.md
```

## Models Compared

* Support Vector Machine (SVM)
* Random Forest
* Adaptive Boosting
* Gradient Boosting

Models were built using **Scikit-learn Pipelines** with **GridSearchCV** for hyperparameter tuning.

## Results

Best performance achieved by:
**Random Forest Regressor** with the lowest MSE.

Top features influencing salary:

* Experience level
* Company size
* Required skills
* Remote ratio

## Technologies Used

* Pandas, NumPy, Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebooks
