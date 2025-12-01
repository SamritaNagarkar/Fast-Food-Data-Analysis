# Fast-Food-Data-Analysis
Data Analysis of fast food chains (McDonalds, KFC, Subway, Burger King)

This project analyzes major aspects of the fast-food industry by combining nutritional data, public sentiment, and real-time popularity trends. The goal is to understand how healthy different fast-food brands are, how the public feels about them, and whether healthier brands are also more popular.

The project uses a Kaggle Fast Food Nutrition dataset and enriches it with two live data sources:

1) Google Trends Search Popularity (for brand visibility)
2) Reddit Sentiment Analysis using VADER (for public opinion)

After cleaning and preparing the dataset, multiple research questions were explored:

1. Which fast-food chain is the healthiest?
We analyzed average Calories, Sodium, Total Fat, and Sugars and ranked each company based on overall nutritional quality.

2. Does a healthier brand tend to be more popular?
We created a simple health score and compared it to live Google Trends popularity to look for relationships.

3. Which brand offers the best overall value (health + popularity + sentiment)?
We normalized metrics and created a combined overall score to rank each company.

4. Are healthier brands viewed more positively online?
We compared each company’s average health score with Reddit sentiment scores to check whether nutritional quality aligns with consumer opinion.

5. Which items contribute most to high calorie and sodium levels?
We identified the most “risky” menu items by analyzing the distribution of extreme nutritional values.


Key Techniques Used

1. Data cleaning and preprocessing
2. Feature engineering
3. Google Trends API (PyTrends)
4. Reddit scraping + VADER sentiment analysis
5. Merging real-time external data with static datasets
6. EDA (plots, ranking, correlations)
7. Deriving custom metrics such as health_score and overall_score


Tech Stack- Python, Pandas, Matplotlib, PyTrends, Requests API, VADER Sentiment Analyzer, Regex

