# MindEase: Mental Health Data Analysis Project

##  Project Overview

MindEase is a comprehensive data analysis project focused on understanding mental health patterns across different age groups and genders. This project employs machine learning techniques to analyze psychological factors and their relationships with overall mental health scores.

##  Project Objectives

- Analyze mental health data across age groups (35-55 and 55+)
- Compare psychological coping mechanisms between genders
- Build predictive models for mental health outcomes
- Visualize correlations between different psychological factors

##  Project Structure

```
MindEase/
├── Source/
│   └── Mindease_.ipynb          # Main analysis notebook
├── requirements.txt             # Project dependencies
└── README.md                   # Project documentation
```

##  Technical Stack

- **Python 3.10.7**
- **Data Analysis**: pandas, numpy
- **Machine Learning**: scikit-learn, xgboost
- **Visualization**: plotly, matplotlib, seaborn
- **Data Processing**: openpyxl for Excel file handling

##  Key Outputs and Findings

### 1. Demographic Analysis
- **Age Distribution**: Analysis of participants aged 35+ divided into two groups:
  - Age 35-55
  - Age 55+
- **Gender Breakdown**: Comparative analysis between male and female participants
- **Interactive Visualizations**: Bar charts showing gender distribution across age groups

### 2. Correlation Analysis
- **Feature Correlation Matrix**: Interactive heatmap showing relationships between:
  - Behavioral Control
  - Emotion-focused Coping
  - Problem-focused Coping
  - Depression Scores
  - Anxiety Scores
  - Avoidant Coping
  - Age factors

### 3. Machine Learning Model Performance

The project implements and compares four different machine learning models:

| Model | Performance Metrics |
|-------|-------------------|
| **XGBoost** | High accuracy with feature importance analysis |
| **Random Forest** | Ensemble method with interpretable results |
| **K-Nearest Neighbors** | Instance-based learning approach |
| **Linear Regression** | Baseline linear model |

#### Model Evaluation Metrics:
- **Mean Absolute Error (MAE)**
- **R² Score (Coefficient of Determination)**
- **Accuracy Percentage**

### 4. Feature Importance Analysis
- Identification of the most influential psychological factors
- Visual representation of feature contributions to mental health outcomes
- Separate analysis for tree-based models (XGBoost and Random Forest)

### 5. Subgroup Analysis
Performance comparison across different demographic groups:
- **Age-based Groups**: 35-55 vs 55+
- **Gender-based Groups**: Male vs Female
- **Sample Size Impact**: Analysis of model performance with varying dataset sizes

##  Visualizations Generated

1. **Interactive Bar Charts**: Gender distribution across age groups
2. **Correlation Heatmaps**: Absolute correlation values between psychological factors
3. **Model Comparison Charts**: Accuracy comparison across different algorithms
4. **Feature Importance Plots**: Top contributing factors for mental health predictions
5. **Performance Trends**: Model accuracy across different sample sizes
6. **Pair Plots**: Scatter plot matrices showing relationships between variables

##  Key Insights

### Psychological Factors
- Behavioral control shows significant correlation with overall mental health
- Coping mechanisms vary between age groups and genders
- Depression and anxiety scores are strong predictors of overall mental wellness

### Model Performance
- XGBoost demonstrates superior performance for this dataset
- Random Forest provides good interpretability with competitive accuracy
- Model performance varies across different demographic subgroups

### Demographic Patterns
- Age groups show distinct patterns in coping strategies
- Gender differences are evident in emotional processing approaches
- Sample size significantly impacts model reliability

##  Getting Started

### Prerequisites
```bash
Python 3.10.7 or higher
Virtual environment (recommended)
```

### Installation
1. Clone the repository
2. Create a virtual environment:
   ```bash
   python -m venv .venv
   ```
3. Activate the virtual environment:
   ```bash
   .venv\Scripts\activate  # Windows
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Analysis
1. Open `Source/Mindease_.ipynb` in Jupyter Notebook or VS Code
2. Run all cells to reproduce the analysis
3. View interactive plots and model results

## 📋 Dependencies

See `requirements.txt` for complete list of dependencies:
- pandas>=2.0.0
- numpy>=1.24.0
- scikit-learn>=1.3.0
- xgboost>=2.0.0
- plotly>=5.15.0
- matplotlib>=3.7.0
- seaborn>=0.12.0
- openpyxl>=3.1.0

##  Future Enhancements

- [ ] Deep learning model implementation
- [ ] Time-series analysis for longitudinal data
- [ ] Additional demographic factors analysis
- [ ] Web dashboard for interactive exploration
- [ ] Model deployment for real-time predictions

##  Sample Output Previews

### Model Accuracy Comparison
```
XGBoost - MAE: X.XX, R² Score: 0.XX, Accuracy: XX.XX%
Random Forest - MAE: X.XX, R² Score: 0.XX, Accuracy: XX.XX%
KNN - MAE: X.XX, R² Score: 0.XX, Accuracy: XX.XX%
Linear Regression - MAE: X.XX, R² Score: 0.XX, Accuracy: XX.XX%
```

### Subgroup Performance
```
🔹 Model Performance Across Groups:
Age 35-55 - MAE: X.XX, R² Score: 0.XX
Age 55+ - MAE: X.XX, R² Score: 0.XX
Male - MAE: X.XX, R² Score: 0.XX
Female - MAE: X.XX, R² Score: 0.XX
```

##  License

This project is for educational and research purposes.

##  Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for improvements.

---

**Note**: This project analyzes anonymized mental health data and follows ethical guidelines for psychological research. All visualizations and models are designed to promote understanding of mental health patterns while maintaining participant privacy.
