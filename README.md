## Data Science Life Cycle Project: DC 311 Service Requests

### Project Overview

The purpose of this project is to walk through the entire data science life cycle, from data collection to insightful analysis and predictive modeling. 

For this project, I’ve chosen a dataset from **DC’s 311 City Service Requests in 2024**. This dataset represents non-emergency service requests made by residents in Washington, D.C.

This dataset serves as a critical resource for understanding how city services are utilized, analyzing resource allocation, and providing actionable insights to improve service delivery.

### Key Highlights

#### Data Preparation
- Cleaned raw data and handled missing values.
- Encoded categorical features and selected relevant variables for analysis.

#### Predictive Modeling
- **Random Forest Regressor**:
  - Initial model with an R² score of 0.457 and MAE of 152.73 hours.
  - Identified key features like SERVICECODEDESCRIPTION and season.
- **XGBoost**:
  - Improved performance with an R² score of 0.995 and MAE of 21.6 hours.
  - Delivered highly accurate predictions for service resolution times.

#### Clustering Analysis
- Applied **K-Means Clustering** to identify patterns in service requests.
- Used the elbow method and PCA visualization to group similar request types.
- Insights gained support resource planning and service efficiency improvements.

### Conclusion

This project demonstrated the power of data science and machine learning in solving real-world problems. It highlighted the iterative process of refining models, analyzing results, and extracting actionable insights. By improving prediction accuracy and uncovering hidden patterns, this analysis provides valuable strategies for optimizing public services and resource allocation in cities like Washington, D.C.
