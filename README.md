# Customer Churn Prediction Project

## Project Overview
This project focuses on developing a machine learning model to predict customer churn for a telecommunications company. By analyzing various customer attributes and behaviors, the model aims to identify customers who are likely to discontinue their services.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Project Structure](#project-structure)
- [Key Features](#key-features)
- [Methodology](#methodology)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Key Insights](#key-insights)
- [Technologies Used](#technologies-used)
- [Author](#author)

## Data Description
The project uses the "Telco_customer_churn.xlsx" dataset with 7,043 customer records and 33 features, including:
- Demographic information (Gender, Senior Citizen, Partner, Dependents)
- Service details (Phone Service, Internet Service, Contract Type)
- Financial metrics (Monthly Charges, Total Charges, Customer Lifetime Value)
- Churn-related columns (Churn Label, Churn Value, Churn Score)

## Project Structure
```
Churn_Project/
│
├── Telco_customer_churn.xlsx   # Raw dataset
├── Churn_Project.ipynb  # Main Jupyter notebook
└── README.md
```

## Key Features
- Comprehensive customer churn analysis
- Advanced feature engineering
- Synthetic data generation
- Machine learning modeling
- Performance evaluation and visualization

## Methodology
1. Data Preprocessing
   - Cleaned and encoded categorical variables
   - Scaled numerical features
   - Handled missing values

2. Synthetic Data Generation
   - Created an improved synthetic data generator
   - Mimicked real data distribution and patterns

3. Machine Learning Modeling
   - Used Random Forest Classifier
   - Performed grid search for hyperparameter tuning
   - Evaluated model performance

## Results
- Achieved Synthetic Data Model Accuracy: 92.83%
- By using the training dataset build the synthetic data.

### Key Feature Importances
1. Churn Score
2. Tenure Months
3. Monthly Charges
4. Customer Lifetime Value (CLTV)
5. Contract Type

## Installation

### Prerequisites
- Python 3.8+
- Jupyter Notebook or JupyterLab
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

### Setup
```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
cd customer-churn-prediction
pip install -r requirements.txt
```

## Usage
1. Open the Jupyter notebook
2. Run cells sequentially
3. Modify parameters as needed
4. Explore visualizations and model performance

## Key Insights
- Month-to-month contracts have higher churn rates
- Monthly charges significantly impact customer retention
- Longer tenure correlates with lower churn probability

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Faker (for synthetic data generation)

## Author
Surbhit Jangra
- Date: February 2025

## License
MIT License

## Future Work
- Experiment with more advanced models
- Incorporate more feature engineering techniques
- Develop a real-time churn prediction system

---
