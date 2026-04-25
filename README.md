# career-progression-analysis
# Career Progression & Promotion Gap Analysis

## Overview

In this project, I worked with employee data to understand how career growth (like promotions and role changes) affects whether people stay in a company or not. Instead of directly predicting attrition, I focused more on *why* employees might eventually leave.

## Objective

The main goal was to:

* Find employees who are not growing in their roles
* Identify long gaps between promotions
* Spot employees who haven’t left yet but might in the future

## Dataset

The dataset includes details like:

* Job role and department
* Years in the company
* Years since last promotion
* Training taken
* Manager experience
* Attrition (whether the employee left or not)

## Tools Used

* Python
* Pandas
* Matplotlib & Seaborn
* Jupyter Notebook

## What I Did

### 1. Data Exploration

I started by understanding the dataset, checking columns, and looking at basic statistics. I also checked if there were any missing values.

### 2. Analysis

I explored things like:

* How promotion gaps relate to attrition
* Which departments have more stagnation
* Whether training has any impact on growth

### 3. Feature Creation

To make the analysis better, I created a few simple columns:

* Promotion Gap (years since last promotion)
* Promotion Gap Level (Low / Medium / High)
* Stagnation Flag (if someone is stuck in the same role)
* Training Need (low training participation)

### 4. Retention Opportunity

One important part of the project was identifying employees who:

* Haven’t left the company
* But have high promotion gaps

These employees might leave in the future if nothing changes.

## Key Insights

* Employees with long promotion gaps are more likely to leave
* Less training is often linked with stagnation
* Some roles and departments show slower growth
* Manager experience seems to affect employee progression

## Conclusion

From this project, I understood that employees don’t suddenly leave — in many cases, they stay for a while without growth and then decide to move on.

This kind of analysis can help companies take action early, like giving promotions, training, or role changes.

## Future Improvements

* Build a dashboard using Power BI
* Try basic clustering for grouping employees
* Add more insights and visualizations

---

This project was done as part of my data analyst internship to practice real-world data analysis and understand business problems better.
