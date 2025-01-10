# Project Overview

This capstone project analyzes and predicts the success of SpaceX Falcon 9 rocket launches using data science techniques. The primary objective is to understand the factors that influence launch success and to build predictive models that can determine whether a rocket's first stage will successfully land. These insights are crucial for estimating launch costs and improving future space missions.

# Objectives

1. Identify factors that determine the success of a rocket landing.
2. Analyze the relationship between operational conditions and success rates.
3. Develop machine learning models to predict landing outcomes.

# Data Collection

- Sources:

  - SpaceX REST API
  - Wikipedia (scraped using BeautifulSoup)
    
- Processes:
  
  - Retrieved and cleaned data using Python and Pandas.
  - Exported processed data to CSV for further analysis.

# Methodology

1. Data Wrangling:
- One-hot encoding for categorical features.
- Handling missing values and inconsistencies.
2. Exploratory Data Analysis (EDA):
- SQL-based queries for identifying trends.
- Visualizations to explore relationships between features.
3. Interactive Analytics:
- Folium for mapping launch site locations and outcomes.
- Plotly Dash for interactive dashboards.
4. Predictive Modeling:
- Classification models with GridSearchCV for hyperparameter tuning.
- Model evaluation using accuracy scores and confusion matrices.
  
# Tools and Libraries

- Data Handling: Pandas, SQL
- Visualization: Matplotlib, Seaborn, Folium, Plotly Dash
- Machine Learning: Scikit-learn

# Key Findings

1. Launch Sites: Success rates are higher at specific sites like KSC LC-39A.
2. Payload: Heavier payloads generally result in higher success rates for certain orbits (LEO, ISS).
3. Orbits: Success is orbit-dependent, with ES-L1, GEO, and SSO having the highest rates.
4. Time Trends: Launch success rates have steadily increased from 2013 to 2020.
5. Model Performance: Decision Tree Classifier achieved the highest accuracy at 87.3%.

# Visual Insights

  - Correlation Heatmap: Shows the relationship between payload, orbit, and success rate.
  - Folium Maps: Interactive maps showing launch site proximities and outcomes.
  - Dashboards: Pie charts and scatter plots for visual summaries.
    
# Predictive Modeling

  - Best Model: Decision Tree Classifier with 87.3% accuracy.
  - Confusion Matrix: Highlighted minimal Type 1 errors.
    
# Conclusion

This project demonstrates the application of data science in solving real-world problems in space exploration. By analyzing historical data and building predictive models, it provides actionable insights for improving the success rates of rocket launches.

