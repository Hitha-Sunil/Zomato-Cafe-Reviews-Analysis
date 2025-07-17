# Zomato-Cafe-Reviews-Analysis
A comprehensive sentiment analysis and exploratory data analysis (EDA) project on Zomato cafe reviews, identifying top-performing cafes, customer sentiment by location, and key drivers of satisfaction.

This repository contains a comprehensive analysis of Zomato cafe reviews, aiming to provide actionable insights into customer satisfaction, cafe performance, and culinary trends across various cities. The project leverages sentiment analysis, topic modeling (LDA & LSA), and extensive data visualization to uncover key patterns and inform business strategies.

# About the Dataset
The analysis is based on the CafeCritic: A Flavorful Dataset of Cafe Reviews dataset. This comprehensive dataset captures genuine customer experiences and includes the following key information for each review entry:<br>


**Index**: A unique identifier for each review entry.

**Name**: The name of the cafe being reviewed.

**Overall Rating**: The overall rating provided by the reviewer.

**Cuisine**: The type of cuisine offered by the cafe.

**Rate for Two**: The average cost for two people dining at the cafe.

**City**: The city where the cafe is located.

**Review**: A detailed review written by the customer, capturing their experience.

# Project Objectives

**Identify Top-Performing Cafes**: Highlight cafes that excel in customer satisfaction across various cities by analyzing positive reviews, enabling targeted recognition of successful businesses.


**Filter Customer Sentiment by Location**: Group reviews by cities to understand regional variations in customer experiences and identify areas with the most satisfied or unsatisfied customers.


**Visualize Trends for Decision-Making**: Utilize bar charts and sentiment analysis visualizations to interpret cafe performance, facilitating data-driven decisions for improvements in service, product offerings, or marketing strategies.

# Analysis and Key Findings
This project involves the following key analytical steps and provides valuable insights:

**1. Data Preprocessing**
The raw review text data undergoes a thorough preprocessing pipeline, including:<br>




Removal of punctuation and numbers.

Conversion to lowercase.

Tokenization of text.

Removal of stopwords.

Lemmatization of tokens.

**2. Sentiment Analysis**
Customer reviews are analyzed to determine their sentiment (Positive, Negative, or Neutral). This helps in understanding overall customer satisfaction.





**3. Topic Modeling (LDA & LSA)**
Latent Dirichlet Allocation (LDA) and Truncated Singular Value Decomposition (LSA) are applied to extract key themes and topics from the review texts. Common themes observed include food quality, taste, ambiance, and service.

**4. Key Visualizations and Inferences**

Sentiment Category Distribution: A pie chart illustrates the distribution of positive, negative, and neutral sentiments across all reviews.


Top 10 Cafes with Most Positive/Negative Reviews: Donut charts identify cafes excelling in customer satisfaction and those struggling, highlighting opportunities for targeted improvements.



Average Sentiment Score by City: Bar charts visualize the average sentiment score across different cities, helping identify regions with the most satisfied or unsatisfied customers.



Top Items Ordered: Word clouds and bar charts display the most frequently ordered items and cuisines, providing insights into popular offerings and customer purchasing behavior.



Heatmap of Rate for Two and Sentiment Score: This visualization explores the relationship between the average cost for two people and the sentiment score, suggesting a correlation where higher rates are associated with positive sentiment.


Average Sentiment Score by Review Length Categories: A bar chart shows how sentiment varies with review length (Short, Medium, Long).

# Conclusion
The sentiment analysis reveals significant variability in customer satisfaction across cafes and cities. Factors like food quality, ambiance, and service are crucial drivers of positive reviews. By identifying high-performing cafes and addressing common complaints in underperforming ones, businesses can improve customer satisfaction and loyalty.
