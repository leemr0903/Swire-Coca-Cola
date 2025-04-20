# Swire-Coca-Cola Delivery Optimization

## Overview
This capstone project for the University of Utah MSBA program focused on helping Swire Coca-Cola optimize delivery routing by balancing cost efficiency with customer growth potential. Using a combination of descriptive, predictive, and prescriptive analytics, we built a dashboard and linear regression model to support data-driven routing decisions.

## Business Problem
Swire Coca-Cola operates multiple delivery truck types (Red Truck and White Truck), each with different cost structures and service levels. The company needed help identifying which customers to transition to more cost-effective delivery methods without sacrificing sales growth or customer experience.

## Objectives
- Build a regression model to predict total units ordered by customer.
- Segment customers based on volume and potential to optimize delivery assignments.
- Provide actionable insights through a Tableau dashboard and customer routing recommendations.

## Data and Methodology
- **Data Sources:** Swire-provided order data, customer info, and delivery attributes (aggregated at the customer-day level).
- **EDA & Feature Engineering:** Created metrics such as `Total Units Ordered`, `Loaded Difference`, and `Shipment Difference`. Removed features with near-zero variance or multicollinearity.
- **Modeling:** Linear regression was selected for interpretability and model performance.
- **Evaluation Metrics:**
  - Adjusted R² (2023): 0.60
  - RMSE (2023): 81.90
  - Adjusted R² (2024): 0.57
  - RMSE (2024): 92.6

## Key Contributions
This repository includes:
- 📊 **EDA Notebook** – Exploratory data analysis and feature creation
- 🔍 **Modeling Notebook** – Regression modeling and evaluation
- 📈 **Tableau Dashboard** – Interactive dashboard for routing decisions
- 🎯 **Final Presentation** – Summary of findings and recommendations

## Individual Contributions
As part of Group 1, I contributed to:
- Engineering response variables and predictors for modeling
- Addressing multicollinearity through VIF filtering
- Structuring the Tableau dashboard to highlight customer growth trends and routing status
- Drafting final recommendations to Swire based on clustering and regression results

## Challenges & Learnings
- **Multicollinearity:** Required careful removal of aliased variables and high-VIF features.
- **Time Lag & Forecasting:** Sales patterns showed time-dependent trends; limited timeline prevented implementation of time series forecasting.
- **Data Limitations:** Lack of order-level granularity and ZIP codes restricted segmentation accuracy.

## Business Impact
- Delivered data-driven routing recommendations that reduce delivery costs and preserve growth potential.
- Created scalable workflows and dashboards for Swire to use in future quarters.
- Provided strategic insights to identify at-risk or misclassified accounts and adjust delivery methods accordingly.

