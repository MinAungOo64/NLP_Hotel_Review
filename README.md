# NLP_Hotel_Review

## Description
This repository demonstrates a small project to perform mainly on **Exploratory Data Analysis (EDA)**. The project utilizes the **Trip Advisor Hotel Reviews** dataset from Kaggle to analyze hotel reviews and predict the sentiment of the reviews (positive or negative).

## Dataset

The dataset used in this project is the **Trip Advisor Hotel Reviews** dataset, which contains hotel reviews from Trip Advisor. Each review has the following attributes:
- **Review**: The text of the hotel review.
- **Rating**: The rating given by the reviewer (scale of 1-5).

You can access the dataset on Kaggle here:  
[Trip Advisor Hotel Reviews Dataset](https://www.kaggle.com/datasets/andrewmvd/trip-advisor-hotel-reviews)

### Data Columns
- **Review**: The text of the hotel review.
- **Rating**: The review rating given by the user (1-3 = negative, 4-5 = positive).

## Key Objectives
The main objectives of this project are:
1. Perform **Exploratory Data Analysis (EDA)** on the hotel reviews to understand data distribution and trends.
2. Perform simple **Sentiment Analysis** model using **Hugging Face Transformers** to classify the reviews as positive or negative.

## Approach

1. **Exploratory Data Analysis (EDA)**:
   - Data loading and basic statistics.
   - Visualizations to understand the distribution of ratings and sentiments.
   - Text analysis to understand common words in reviews.

2. **Sentiment Analysis**:
   - Use the Hugging Face `transformers` library to fine-tune a pre-trained transformer model (e.g., BERT) for sentiment analysis.
