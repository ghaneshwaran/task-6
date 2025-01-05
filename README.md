name: rithigha.r
intern id:CT08DS276
Project Report: Big Data Sentiment Analysis Using PySpark
Objective
To analyze large-scale textual data and classify sentiments (positive or negative) by leveraging PySpark's distributed processing capabilities. This project demonstrates the scalability of big data tools for handling datasets that exceed local machine memory.

Dataset Overview
Dataset Name: Large-Scale Product Reviews
Size: Hundreds of thousands of records
Columns:
Rating: Numerical values (1 to 5) representing product ratings.
Review: Textual feedback from customers.
Methodology
1. Environment Setup
A Spark Session was initialized to enable distributed processing of the dataset.
2. Data Loading
The dataset was ingested into a PySpark DataFrame, enabling efficient handling of large-scale data.
3. Data Preprocessing
Neutral ratings (Rating = 3) were excluded to focus on binary sentiment classification:
Ratings > 3: Positive sentiment (Label: 1)
Ratings <= 3: Negative sentiment (Label: 0)
Text in the Review column was cleaned by:
Converting to lowercase.
Removing special characters and non-alphabetical symbols.
4. Exploratory Data Analysis
The sentiment distribution was calculated to understand the balance between positive and negative reviews.
Results
Sentiment Distribution
Positive Reviews: ~X% of the dataset.
Negative Reviews: ~Y% of the dataset.
Performance
The preprocessing and analysis tasks were completed efficiently, demonstrating the scalability of PySpark for large datasets.
Key Insights
Most reviews are [positive/negative], indicating [a general trend of customer satisfaction/dissatisfaction].
The preprocessing pipeline effectively cleaned and prepared the data for further analysis or machine learning.
Future Work
Feature Engineering: Extract insights such as the most frequent words in positive and negative reviews.
Machine Learning: Train a distributed sentiment classification model using Spark MLlib.
Visualization: Create interactive dashboards to explore trends in the dataset.<img width="226" alt="intern 4" src="https://github.com/user-attachments/assets/0084e44b-e30a-4cc9-a9d5-4ce19f68dd1b" />
<img width="353" alt="intern 3" src="https://github.com/user-attachments/assets/0c48a713-2361-4146-8739-11c1e1fa7b8d" />
