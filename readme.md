Zomato Restaurant Market Analysis (EDA)

## Overview
This project performs an Exploratory Data Analysis (EDA) on a dataset of Zomato restaurants. **This analysis is a recreation of a project originally published by [GeeksforGeeks](https://www.geeksforgeeks.org/data-analysis/zomato-data-analysis-using-python/)**, built to practice data cleaning and visualization techniques. 

The goal is to uncover business insights regarding restaurant types, customer ratings, pricing, and the impact of online ordering capabilities. The goal is to uncover business insights regarding restaurant types, customer ratings, pricing, and the impact of online ordering capabilities. 

This analysis can help stakeholders (restaurant owners, investors, or food delivery platforms) understand market dynamics and customer preferences.

## Key Objectives
* Identify the most popular restaurant types based on customer votes.
* Analyze the distribution of customer ratings.
* Determine if offering online ordering positively correlates with higher ratings.
* Examine the relationship between restaurant categories and online ordering availability.

## Tools & Libraries Used
* **Python 3**
* **Pandas & NumPy:** Data manipulation and cleaning.
* **Matplotlib & Seaborn:** Data visualization.
* **Jupyter Notebook:** Interactive coding environment.

## Data Cleaning & Preparation
Before analysis, the data required minor cleaning:
* **Rating Conversion:** The `rate` column was imported as strings (e.g., "4.1/5"). A custom function was built to extract the numerical value and convert it to a float for statistical analysis.

## Key Insights & Visualizations

### 1. Online Ordering vs. Ratings
![Online Orders vs Ratings](images.png/ratings%20comparsion.png)

**Finding:** Offline orders received lower ratings in comparison to online orders which obtained excellent ratings.

### 2. Market Leaders by Votes
**Finding:** The data reveals that **Empire Restaurant** is the market leader in terms of total customer engagement, holding the absolute maximum number of votes across the dataset.

### 3. Restaurant Category Distribution
 ![rating distribution](images.png/rating%20distribution.png)

**Finding:** The majority of restaurants received ratings ranging from 3.5 to 4.

## Conclusion
  "The exploratory data analysis reveals a meaningful relationship between a restaurant's features—such as online ordering—and its overall customer reception. While the market features diverse dining categories from Buffets to Cafes, businesses that adapt to digital ordering trends tend to see distinct variations in their rating distributions. These insights can help future restaurant investors identify high-performing business models."

