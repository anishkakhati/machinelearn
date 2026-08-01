# House Price Prediction using Machine Learning

A complete end-to-end machine learning project that predicts residential house prices using the Ames Housing dataset. This project demonstrates the entire ML workflow, including data preprocessing, feature engineering, model training, evaluation, prediction, and model serialization.

## Features

- Data exploration and analysis
- Missing value handling
- Feature engineering
- Ordinal and One-Hot Encoding
- Feature scaling
- Training multiple regression models
- Cross-validation for model evaluation
- House price prediction
- Export predictions as `submission.csv`
- Save trained model using Pickle

## Project Structure

```
ML_MODEL/
│
├── datasets/
│   ├── train.csv
│   ├── test.csv
│   └── sample_submission.csv
│
├── house_price_prediction/
│   ├── main.ipynb
│   ├── gbr.pkl
│   └── submission.csv
│
└── README.md
```

## Dataset

The project uses the Ames Housing Dataset.

Files used:

- `train.csv`
- `test.csv`
- `sample_submission.csv`

Target Variable:

```
SalePrice
```

## Workflow

```
Load Dataset
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Missing Value Handling
      │
      ▼
Feature Engineering
      │
      ▼
Categorical Encoding
      │
      ▼
Feature Scaling
      │
      ▼
Model Training
      │
      ▼
Cross Validation
      │
      ▼
Model Selection
      │
      ▼
Prediction
      │
      ▼
Save Model
      │
      ▼
Generate Submission File
```

## Machine Learning Models

The notebook compares multiple regression algorithms, including:

- Linear Regression
- Ridge Regression
- Lasso Regression
- ElasticNet
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Support Vector Regressor

The best-performing model is used for final prediction.

## Output

The project generates:

- `submission.csv` – predicted house prices
- `gbr.pkl` – trained Gradient Boosting model

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Pickle
- Jupyter Notebook

## Installation

Clone the repository.

```bash
git clone <repository-url>
```

Install the required packages.

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook.

```bash
jupyter notebook
```

Open `main.ipynb` and run all cells.

## Results

The notebook performs:

- Data cleaning
- Feature preprocessing
- Model comparison
- House price prediction
- Model serialization

The final trained model is stored as a Pickle file for future inference.


## License

This project is intended for educational and learning purposes.
