# global-suicide-analysis
"A Data Science project analysis global suicide trends using Python and machine learning."

- This projects analysis global suicide data to uncover trends by age,gender,country. The goal is predicts suicide rates using machine learning (Random Forest).

## Goal
- Analyze suicide patterns globally across years
- Identify high-risk group based on age, sex, and region
- Build a machine learing model to predics suicide rates per 100,000 population

## Dataset
**Source**:
**Column**:
'year'
'country'
'sex'
'age'
'suicide_no'
'population'
Derived:
'suicide_rate': calculate as (suicide_no/population) * 100000

## Tools & Libraries

**Python**
**Pandas**,**Numpy** -data processing
**Matplotlib**,**seaborn**-data visualization
**Scikit-learn**-machine learning(Random Forst Regressor)
**Jupyter Notebook**-interactive abalysis

##  Exploratory Data Analysis

- Suicide rates by **age group** (boxplots)
- Suicide rate trends over time by **gender**
- High-suicide-rate **countries**
- Correlation heatmaps

##  Machine Learning Model

- **Model**: Random Forest Regressor
- **Target**: Suicide Rate
- **Features**: Encoded year, age, sex, country
- **Performance**:
  - **MAE**: 46.97
  - **RMSE**: 1.70
  

##  Key Insights

- Suicide rates are significantly higher in **males**.
- The **45–54** age group shows the highest risk across countries.
- Some countries consistently show higher suicide rates.
- Population size and age structure impact suicide rates more.

- ##  Future Improvements

- Include GDP or health spending per capita as predictors
- Compare pre- and post-pandemic suicide trends

##  About Me

Aspiring data scientist currently completing my degree. Passionate about real-world impact, health analytics, and machine learning. Looking for internship opportunities in data science and AI (London-based).

 Email:sukriya2609@gmail.com  
 Location: London, UK  
GitHub: [https://github.com/Sukriya-Quayum]
