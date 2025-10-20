# Swedish Unemployment Benefits Analysis (1999-2024)

A comprehensive data analysis and machine learning project examining unemployment benefits trends across Swedish counties from 1999 to 2024.

##  Project Overview
This project analyzes the number of people receiving unemployment benefits across Sweden's counties, identifying regional patterns, temporal trends, and implementing predictive machine learning models.

##  Key Features
- **Data Analysis**: Trends analysis across 21 counties
- **Machine Learning**: Implementation of multiple regression models (Linear, Random Forest, Gradient Boosting)
- **Visualization**: Interactive charts, line plots, and comparative analysis
- **Time Series Analysis**: Examination of trends from 1999-2024

##  Technologies Used
- **Python 3** with Pandas, NumPy for data manipulation
- **Scikit-learn** for machine learning (Linear Regression, Random Forest, Gradient Boosting)
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Data Processing**: Missing value handling, feature scaling

##  Key Insights
- Identified significant drop in benefit recipients from 1999-2010
- Detected COVID-19 impact with sharp increase in 2020
- Regional disparities with Stockholm, Västra Götaland, and Skåne having highest numbers
- Random Forest achieved best performance (R² = 0.953) in predictions

##  Project Structure
1. **Data Extraction & Transformation**
   - Data cleaning and preprocessing
   - Handling missing values and duplicates

2. **Exploratory Data Analysis**
   - Temporal trends analysis
   - Regional distribution analysis
   - Interactive visualizations

3. **Machine Learning Modeling**
   - Multiple regression models comparison
   - Model evaluation and performance metrics
   - Prediction error analysis

##  Model Performance
| Model | R² Score | MAE | MSE |
|-------|----------|-----|-----|
| Linear Regression | 0.134 | 13,970 | 546M |
| Random Forest | 0.953 | 2,571 | 29M |
| Gradient Boosting | 0.934 | 3,120 | 41M |

##  How to Run
Note: Data files will be made available in the repository shortly. Please check back later for full access to the source datasets.
1. Open the notebook in Google Colab
2. Install required packages: `!pip install pandas numpy matplotlib seaborn plotly scikit-learn`
3. Run cells sequentially to reproduce analysis
4. Ensure data file path is correctly specified

##  Files Included
- `unemployment_benefits.ipynb` - Main analysis notebook
- Processed data exports
- Visualization exports

##  Future Enhancements
- Incorporate demographic data for deeper insights
- Add more advanced time series forecasting
- Include economic indicators for contextual analysis
