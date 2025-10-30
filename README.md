# Employee Attrition Analysis & Prediction

A comprehensive data analysis and machine learning project examining employee attrition patterns using IBM HR Analytics data. This project identifies key factors contributing to employee turnover and builds a predictive model to help HR departments proactively manage retention.

## 📊 Project Overview

Employee attrition is a critical challenge for organizations, impacting productivity, morale, and bottom-line costs. This project analyzes employee data to:

- Identify key factors contributing to employee attrition
- Perform statistical hypothesis testing to validate insights
- Build a predictive model to forecast attrition risk
- Provide actionable recommendations for HR teams

## 🎯 Key Findings

### Major Attrition Drivers

1. **Overtime Work**: Employees working overtime show significantly higher attrition rates
2. **Income Levels**: Lower monthly income correlates with increased turnover
3. **Job Satisfaction**: Lower satisfaction scores predict higher attrition risk
4. **Work-Life Balance**: Poor work-life balance increases likelihood of departure

### Model Performance

- **Accuracy**: 86.73%
- **Model Type**: Logistic Regression
- **Key Predictors**: Overtime status and Monthly Income

## 📁 Dataset

The analysis uses the IBM HR Analytics Employee Attrition dataset, which includes:

- **1,470 employee records**
- **35 features** including demographics, job characteristics, satisfaction metrics, and compensation
- **Target Variable**: Attrition (Yes/No)

### Key Features Analyzed

- Age, Gender, Marital Status
- Department, Job Role, Job Level
- Monthly Income, Salary Hike Percentage
- Years at Company, Years in Current Role
- Job Satisfaction, Work-Life Balance
- Overtime Status, Business Travel Frequency
- Distance from Home

## 🛠️ Technologies Used

- **Python 3.x**
- **Libraries**:
  - `pandas` - Data manipulation and analysis
  - `numpy` - Numerical computing
  - `matplotlib` - Data visualization
  - `seaborn` - Statistical visualizations
  - `scipy` - Statistical testing
  - `scikit-learn` - Machine learning models

## 📈 Analysis Pipeline

### 1. Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Distribution analysis of key variables
- Correlation analysis
- Visualization of attrition patterns across different factors

### 2. Statistical Hypothesis Testing
- Chi-square tests for categorical variables
- Independent t-tests for continuous variables
- Validation of attrition drivers with statistical significance

### 3. Predictive Modeling
- Feature selection based on EDA and hypothesis testing
- Logistic Regression model training
- Model evaluation and performance metrics
- Attrition probability predictions

### 4. Insights & Recommendations
- Business implications of findings
- HR intervention strategies
- Risk scoring for current employees


## 📊 Visualizations

The notebook generates several visualizations including:

- Attrition rate distributions
- Correlation heatmaps
- Comparative boxplots and bar charts
- Model performance metrics
- Feature importance plots

## 💡 Business Applications

This analysis can help organizations:

1. **Identify At-Risk Employees**: Score employees on attrition probability
2. **Targeted Retention Programs**: Focus resources on high-risk groups
3. **Policy Optimization**: Test "what-if" scenarios for policy changes
4. **Proactive HR Management**: Early intervention before employees decide to leave
5. **Resource Allocation**: Better budgeting for recruitment and retention

## 🔍 Key Insights for HR Teams

### Actionable Recommendations

- **Manage Overtime**: Implement policies to reduce excessive overtime work
- **Competitive Compensation**: Review and adjust salary structures to market rates
- **Work-Life Balance**: Promote flexible working arrangements
- **Career Development**: Create clear career progression pathways
- **Regular Check-ins**: Monitor satisfaction through pulse surveys

### Predictive Scenarios

The model can predict attrition risk based on employee characteristics:

- **High Risk**: Overtime workers with low income (41.5% attrition probability)
- **Low Risk**: No overtime with high income (3.1% attrition probability)

## 📝 Project Structure

```
employee-attrition-analysis/
│
├── Employee_Attrition.ipynb    # Main analysis notebook
├── README.md                    # Project documentation
└── data/                        # Dataset directory
    └── WA_Fn-UseC_-HR-Employee-Attrition.csv
```

## 🔮 Future Enhancements

- [ ] Incorporate additional features into the predictive model
- [ ] Experiment with advanced algorithms (Random Forest, XGBoost, Neural Networks)
- [ ] Develop an interactive dashboard for HR teams
- [ ] Implement real-time scoring for new employees
- [ ] Add time-series analysis for attrition trends
- [ ] Create automated reporting pipeline

## 📊 Model Limitations

- Uses only 2 primary features (overtime and income) - expansion could improve accuracy
- Assumes linear relationships between variables
- Requires periodic retraining as workforce dynamics change
- Historical data may not capture all organizational changes


---

**Note**: This project is for educational and analytical purposes. Always consult with HR professionals and legal counsel when implementing employee management strategies.
