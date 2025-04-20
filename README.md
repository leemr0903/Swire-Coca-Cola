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
- [**Business Problem Statement**](./BusinessProblemStatement_MadelineLee.docx): Defines the business challenge, project objectives, and analytics goals as submitted to the sponsor and course faculty.
- [**EDA Notebook (RMarkdown)**](./LEE_M_SWIRE_EDA.Rmd): Contains data exploration, feature engineering, and insights used to inform modeling decisions.
- [**EDA Summary PDF**](./Group%201%20EDA%20-%20Maddie%20Lee%2C%20Alexia%20Wells%2C%20Leah%20Ekblad%2C%20Whtiney%20Holt%20-%202025.02.22.pdf): Visual and narrative summary of EDA findings for stakeholder communication.
- [**Modeling Notebook (RMarkdown)**](./LEE_MADDIE_MSBA_CAPSTONE_MODELING%20(1).Rmd): Contains predictive modeling code, VIF filtering, and regression output.
- [**Group Modeling Report (HTML)**](./Group%201%20Modeling%20-%20Maddie%20Lee%2C%20Alexia%20Wells%2C%20Leah%20Ekblad%2C%20Whitney%20Holt%20-%202025.03.18.html): Final group modeling write-up with performance evaluation and business interpretation.
- [**Slide Deck – Final Presentation**](./Group%201%20Slide%20Deck%20(5).pptx): Final stakeholder-facing PowerPoint summarizing methods, results, and business recommendations.
- [**Capstone Overview Slides**](./University%20of%20Utah%20Capstone-Spring%202025%20(1).pptx): General course slide deck that outlines the structure and expectations of the Spring 2025 MSBA Capstone.


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

