# Diabetes EDA and Prediction

A comprehensive exploratory data analysis and machine learning project for predicting diabetes using health indicators from the Behavioral Risk Factor Surveillance System (BRFSS) 2015 survey.

## 📊 Dataset Overview

This project uses three diabetes-related datasets from the BRFSS 2015 survey:

- **diabetes_binary_health_indicators_BRFSS2015.csv**: Original dataset with binary diabetes classification
- **diabetes_binary_5050split_health_indicators_BRFSS2015.csv**: Balanced 50/50 split version for better model training
- **diabetes_012_health_indicators_BRFSS2015.csv**: Multi-class dataset (0 = no diabetes, 1 = prediabetes, 2 = diabetes)

### Key Features
- 21 health indicators including BMI, age, physical activity, diet habits, and medical history
- Large sample sizes for robust analysis
- Real-world health survey data

## 🚀 Installation

1. Clone this repository:
```bash
git clone <repository-url>
cd diabetes_eda_prediction
```

2. Install the required dependencies:
```bash
pip install -r requierments.txt
```

## 📈 Usage

### Exploratory Data Analysis
Open the Jupyter notebook to explore the data:
```bash
jupyter notebook notebook/Diabet_notebook_EDA+Prediction.ipynb
```

The notebook includes:
- Data loading and preprocessing
- Statistical analysis
- Data visualization
- Feature engineering
- Correlation analysis

### Model Training and Prediction
The notebook contains implementations of various machine learning models for diabetes prediction, including:
- Logistic Regression
- Random Forest
- XGBoost
- And more...

## 📁 Project Structure

```
diabetes_eda_prediction/
│
├── README.md                           # Project documentation
├── requierments.txt                    # Python dependencies
│
├── data/                               # Dataset directory
│   ├── diabetes_012_health_indicators_BRFSS2015.csv
│   ├── diabetes_binary_5050split_health_indicators_BRFSS2015.csv
│   └── diabetes_binary_health_indicators_BRFSS2015.csv
│
└── notebook/                           # Jupyter notebooks
    └── Diabet_notebook_EDA+Prediction.ipynb
```

## 📚 Dependencies

- **numpy**: Numerical computing
- **pandas**: Data manipulation and analysis
- **matplotlib**: Data visualization
- **seaborn**: Statistical data visualization
- **ydata-profiling**: Automated EDA reports
- **statsmodels**: Statistical modeling
- **imbalanced-learn**: Handling imbalanced datasets
- **scikit-learn**: Machine learning algorithms
- **xgboost**: Gradient boosting framework

## 🔬 Methodology

1. **Data Exploration**: Understanding distributions, correlations, and patterns
2. **Data Preprocessing**: Handling missing values, feature scaling, encoding
3. **Feature Selection**: Identifying important health indicators
4. **Model Development**: Training multiple ML models
5. **Model Evaluation**: Comparing performance metrics
6. **Insights**: Drawing conclusions from the analysis

## 📊 Key Health Indicators

The datasets include various health indicators such as:
- Demographic information (age, sex, education, income)
- Physical health metrics (BMI, physical activity)
- Lifestyle factors (smoking, alcohol consumption)
- Medical history (high blood pressure, cholesterol)
- Dietary habits and mental health indicators

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Contact

For questions or suggestions, please open an issue in this repository.