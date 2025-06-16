This project analyses a healthcare insurance dataset (USA) to understand how personal and geographic attributes influence medical insurance charges. It identifies key patterns and provides simple predictive models to estimate costs.

The analysis includes:

**Data Cleaning and Transformation (ETL):**

- Handling categorical variables (e.g., smoker, sex, region)
- Creating meaningful features like BMI categories (underweight, normal, overweight, obese)

**Data Visualisation:**

- Exploring trends across age, gender, region, and smoking status
- Correlation analysis of numerical and categorical variables

**Predictive Modelling:**

- Using regression models to predict insurance charges based on user profiles


This project is ideal for demonstrating practical skills in data analysis, feature engineering, and model development using real-world health data.


### Key Technologies:

The following Python tools and libraries are used:
- Jupyter Notebook – For running and explaining code in an interactive format
- pandas – For data loading, cleaning, and transformation
- numpy – For numerical operations and feature creation
- matplotlib & seaborn – For static charts and exploratory data analysis
- plotly – For interactive visualisations
- scikit-learn – For building and evaluating predictive models (e.g., Linear Regression, Decision Trees)

### Use Cases:

The project can be adapted or extended for:

- Healthcare policy planning: Understanding which groups incur higher insurance costs
- Insurance companies: Estimating premiums based on customer profiles
- Personal finance apps: Predicting healthcare-related expenses for users
- Data science portfolios: Showcasing skills in ETL, EDA, feature engineering, and modelling

## Conclusion for Insurance Charges Analysis Project

This project aimed to explore how various personal and lifestyle factors—particularly smoking status and obesity (via BMI)—affect health insurance charges, using the publicly available insurance.csv dataset. We used Python libraries such as Pandas, Plotly, Seaborn, and SciPy for data exploration, visualization, and statistical testing.

# Key Insights:

- Smokers Pay Significantly More

  A box plot comparing smokers and non-smokers revealed that smokers incur significantly higher insurance charges.
  A statistical analysis was of the p-value (< 0.05) from a t-test was not performed due to system errors.
  Visuals show a larger spread and higher median for smokers, with many outliers at the high end.

- Charges Distribution is Right-Skewed

  The distribution plot of insurance charges showed a clear right-skew, with most people paying moderate fees, but a few paying very high amounts. This skewness justifies the use of medians in summary statistics and supports further analysis using log-transformation if needed in modeling.

- Correlation Analysis

  The correlation matrix revealed:

  a) A strong positive correlation between age and charges
  b) BMI and number of children had weaker or no significant linear correlation with charges
  c) Smoker status had a noticeable impact but is a categorical variable, so it doesn't reflect directly in the correlation coefficients.


- Final Takeaways:
  Smoking is the most impactful lifestyle factor in this dataset, strongly associated with higher insurance costs.
  Age and smoking status should be key features in any predictive pricing model for insurance.
  Visualization techniques like box plots, histograms, and correlation matrices are powerful for communicating insights clearly and quickly.
  Further work could include predictive modeling (e.g., linear regression, decision trees) to estimate charges based on multiple features.


