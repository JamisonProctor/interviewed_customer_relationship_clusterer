### Clustering Method Exploration: Analyzing Relationships Between Interviewed and Non-interviewed Customers

#### Project Overview
In this solo data science project, I explore clustering methods with a dataset of 200 customers, including 10 who have undergone in-depth discovery interviews. The goal is to identify patterns and similarities between interviewed and non-interviewed customers, thereby gaining insights into diverse customer needs.

#### Objectives
- **Uncover Similarities:** Utilize clustering algorithms to discover patterns in customer behavior and preferences.
- **Extrapolate Interview Insights:** Apply insights from the interviews to better understand the broader customer base.
- **Enhance Personal Learning:** Use this project to refine data-driven insight delivery skills, with a focus on non-interviewed customers.

#### Approach
The project involves:
- **Data Preprocessing:** Normalizing features such as age, annual income, and spending score, and encoding categorical data like gender.
- **Clustering Analysis:** Using KMeans clustering to categorize customers and identify patterns.
- **Distance Calculation:** Computing Euclidean distances between all data points to understand the proximity of customers within clusters.
- **Closest Point Analysis:** Identifying and analyzing the closest data points to each cluster's centroid to represent each cluster.
- **Interviewee Analysis:** Examining the interviewed customers in the context of their respective clusters and calculating their proximity to the closest points.

#### Data Source
The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/shrutimechlearn/customer-data) and includes:
- **CustomerID:** IDs from 1 to 200.
- **Gender:** 56% Female, 44% Male.
- **Age:** Range 18-70 years.
- **Annual Income:** $15,000 to $137,000.
- **Spending Score:** 1 to 99, indicating purchasing behavior.

This project offers an opportunity to delve deep into data science methodologies, particularly focusing on clustering techniques, to understand customer segments more effectively.
