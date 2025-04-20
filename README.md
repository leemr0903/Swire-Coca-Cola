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

This project provided Swire Coca-Cola with a scalable, analytics-driven approach to improving delivery efficiency while maintaining long-term customer value. Specifically:

- **Data-Driven Delivery Routing:** Our regression model and dashboard enabled Swire to identify which customers could be transitioned from high-touch Red Truck delivery to cost-effective White Truck routes—without jeopardizing future sales. This allows Swire to save on operational costs while preserving service levels for high-potential accounts.

- **Identification of Growth Opportunities:** By segmenting customers into groups such as “Growth Ready” and “At-Risk Misclassified,” we highlighted accounts that may be undervalued using current routing logic. Swire can now proactively support these accounts through field rep engagement or hybrid service models before potential churn occurs.

- **Visual Decision Support:** The interactive Tableau dashboard gives stakeholders real-time visibility into delivery classification, customer trends, and regression-backed volume forecasts. This tool improves collaboration between analytics teams, operations, and sales representatives.

- **Foundations for Forecasting and Automation:** While this project focused on regression modeling, the structure supports future expansion into time series forecasting, machine learning classification, and automated routing recommendations based on projected volume.

- **Strategic Alignment with Efficiency Goals:** The insights and recommendations directly support Swire’s strategic initiative to reduce delivery costs while maximizing customer lifetime value. The tools and models developed can be applied to future customer cohorts and refined with additional data for even greater precision.

Overall, the project demonstrated how a thoughtful blend of descriptive, predictive, and prescriptive analytics can drive operational change, reduce costs, and improve decision-making across business units.

## Lessons Learned

This project taught me that even when the data isn’t perfect or complete, it’s still possible to deliver insights that drive meaningful business impact. Rather than waiting for ideal conditions, we focused on making the most of what was available and were able to create tools and recommendations that improved Swire’s current processes. I also learned the value of working with a team from diverse backgrounds; different skill sets and perspectives helped us create a more well-rounded and thoughtful solution.


