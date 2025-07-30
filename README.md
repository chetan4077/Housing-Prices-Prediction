# House Price Prediction

A machine learning project that predicts house prices using various regression algorithms. The project compares different models to find the most accurate predictor for housing prices.

##  Project Overview

This project implements and compares multiple machine learning algorithms to predict house prices based on various features like location, size, amenities, and other property characteristics. The goal is to build an accurate model that can help estimate property values.

##  Model Performance

| Algorithm | Mean Absolute Error (MAE) |
|-----------|---------------------------|
| **Random Forest** | **$20,000** |
| Decision Tree | $23,000 |

*Random Forest achieved the best performance with the lowest prediction error.*

##  Features

- Data preprocessing and feature engineering
- Multiple regression algorithms implementation
- Model comparison and evaluation
- Visualization of results and model performance
- Error analysis and metrics calculation

##  Technologies Used

- **Python** - Primary programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Scikit-learn** - Machine learning algorithms
- **Matplotlib/Seaborn** - Data visualization
- **Jupyter Notebook** - Development environment

##  Project Structure

```
Housing-Prices-Prediction/
├── data/                   # Dataset files
├── models/                 # Trained model files
├── Data_Cleaning.ipynb     # Code for data Cleaning
└── README.md               # Project documentation
```

##  Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/chetan4077/Housing-Prices-Prediction.git
   cd Housing-Prices-Prediction
   ```

2. **Create virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Run the project**
   ```bash
   jupyter notebook
   ```

##  Methodology

### Data Preprocessing
- Handled missing values and outliers
- Feature scaling and normalization
- Categorical variable encoding
- Feature selection and engineering

### Models Implemented
1. **Random Forest Regressor** ⭐ (Best Performance)
   - Ensemble method combining multiple decision trees
   - Reduces overfitting through averaging
   - MAE: $20,000

2. **Decision Tree Regressor**
   - Single tree-based model
   - Interpretable but prone to overfitting
   - MAE: $23,000

### Evaluation Metrics
- **Mean Absolute Error (MAE)** - Primary metric
- **Root Mean Square Error (RMSE)**
- **R² Score** - Coefficient of determination
- **Cross-validation scores**

##  Key Insights

- Random Forest outperformed Decision Tree by $3,000 in MAE
- Ensemble methods prove more robust for house price prediction
- Feature importance analysis revealed key price drivers
- Model generalization improved through cross-validation

##  Future Improvements

- [ ] Implement additional algorithms (XGBoost, Neural Networks)
- [ ] Feature engineering optimization
- [ ] Hyperparameter tuning using Grid/Random Search
- [ ] Time series analysis for price trends
- [ ] Integration with real estate APIs for live data

##  Requirements

```
pandas>=1.3.0
numpy>=1.21.0
scikit-learn>=1.0.0
matplotlib>=3.4.0
seaborn>=0.11.0
jupyter>=1.0.0
```

⭐ **Star this repository if you found it helpful!**
