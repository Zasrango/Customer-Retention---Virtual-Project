# Customer-Retention---Virtual-Project


# Customer Retention 


Overview 

This project focuses on analyzing customer retention, with the goal of identifying key factors that influence customer loyalty and implementing strategies to reduce churn rates. As a data analyst, I conducted an in-depth analysis of customer behavior, purchase patterns, and engagement metrics to understand the drivers behind customer retention.

Objectives

Identify Key Drivers of Retention: Analyze various customer attributes and behaviors to determine which factors most strongly correlate with long-term retention.

Customer Segmentation: Segment the customer base into distinct groups based on their likelihood to remain loyal or churn, enabling targeted retention strategies.

Predictive Modeling: Build predictive models to forecast which customers are at risk of churning, allowing for proactive intervention.

Data Visualization: Create dashboards and visualizations to present insights and trends to stakeholders, facilitating data-driven decision-making.
Why is this so?

Technologies Used

Excel : For data analysis, modeling, and automation.

Power BI/Tableau: For dashboard creation and reporting. 

Following measures are used in this Project:]

Count OF Churn = CALCULATE(DISTINCTCOUNT('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[Churn]="Yes")

Churn% = CALCULATE([Count OF Churn]/COUNT('01 Churn-Dataset'[Churn]))

Count Of Tech_Support = CALCULATE(DISTINCTCOUNT('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[TechSupport]="Yes")

Count Of Streaming_Movies = CALCULATE(DISTINCTCOUNT('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[StreamingMovies]="Yes")

Dependent% = CALCULATE([Count of Dependent]/COUNT('01 Churn-Dataset'[Dependents]))

Partner% = CALCULATE([Count of partner]/COUNT('01 Churn-Dataset'[Partner]))

![Screenshot (38)](https://github.com/user-attachments/assets/44ef29d6-9353-45dd-8da4-980fae9fea62)
![Screenshot (39)](https://github.com/user-attachments/assets/629165a1-19f8-4e2a-9b79-5a6bf8490f0e)





