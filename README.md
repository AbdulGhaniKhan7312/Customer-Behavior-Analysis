## Project Overview

This project analyzes online shopping behaviors to generate insights for improving marketing strategies. The primary focus is on understanding the browsing behaviors of customers during the busiest months (November and December) and determining the likelihood of purchases. The goal is to identify two main groups:
1. Customers with a low purchase rate.
2. Returning customers.

The results will help inform a new marketing campaign aimed at increasing future sales.

## Dataset

The dataset used in this project is `online_shopping_session_data.csv`, containing information on shopping sessions. Key features include:
- `SessionID`: Unique identifier for each session.
- `Administrative`: Number of pages visited related to administrative tasks.
- `ProductRelated`: Number of product-related pages visited.
- `BounceRates`, `ExitRates`: Metrics for customer behavior on the website.
- `Revenue`: Indicates if a purchase was made during the session.

## Key Steps

1. **Data Exploration**: Initial exploration and understanding of the dataset.
2. **Feature Engineering**: Processing and creating meaningful features from the data.
3. **Modeling**: Building machine learning models to predict customer purchasing behaviors.
4. **Statistical Analysis**: Applying binomial distribution to evaluate the probability of achieving specific sales targets based on customer segments.
5. **Results**: Insights on how an increase in purchase rates could impact overall sales.

## Libraries

- Python 3.x
- Pandas
- SciPy
