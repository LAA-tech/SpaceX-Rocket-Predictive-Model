# SpaceX-Rocket-Predictive-Model

## Overview
Space Y is a data analysis project aimed at predicting the reusability of SpaceX's first stage rockets. By leveraging machine learning techniques and SpaceX's public data, we aim to provide insights into launch cost estimation and competitive strategy within the space industry.

## Project Goals
1. Determine the price of each SpaceX launch.
2. Predict the likelihood of SpaceX reusing the first stage rocket.

## Methodologies
### Data Collection
- Utilized SpaceX REST API and web scraping for data retrieval.

### Data Analysis
- **Data Wrangling:** Categorized landing outcomes to create a 'Class' column for predictive modeling.
- **Exploratory Data Analysis (EDA):** Conducted using visualization tools and SQL to analyze flight and payload data, success rates by orbit, yearly trends, and site insights.
- **Interactive Visual Analytics:** Employed Folium and Plotly Dash for dynamic data exploration.
- **Predictive Analysis:** Built and optimized classification models (Logistic Regression, SVM, Decision Tree, K-Means) using GridSearchCV for optimal hyperparameters.

### Findings
- **Exploratory Data Analysis (EDA):**
  - Identified key insights such as flight and payload distributions, success rates by orbit, and site-specific trends.
- **SQL Query Results:**
  - Discovered significant events like the first successful ground landing and performance benchmarks for drone ship landings.
- **Predictive Analysis:**
  - Achieved 0.83 accuracy with Logistic Regression, SVM, and K-Means models on test data; noted challenges with negative predictions in Decision Tree model.

## Usage
To replicate our analysis:
1. Clone the repository.
2. Install necessary dependencies.
3. Run notebooks for data collection, analysis, and predictive modeling.

## Technologies Used
- Python
- Jupyter Notebooks
- Pandas, NumPy, Scikit-learn
- SQL
- Folium, Plotly Dash

## Conclusion
Space Y's analysis provides actionable insights for navigating the competitive landscape of space commerce, focusing on cost-effective strategies and predictive modeling for SpaceX's first stage reusability.

---

For detailed code and analysis, please refer to the project notebooks and files in this repository.
