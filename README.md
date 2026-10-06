# Airbnb Reviews Sentiment Analysis

## Project Overview

This project analyzes Airbnb customer reviews using Natural Language Processing (NLP) techniques to understand customer sentiment and identify frequently mentioned themes in guest feedback. The project uses VADER Sentiment Analysis to classify reviews into Positive, Neutral, and Negative categories and derives meaningful business insights from the results.

## Objectives

* Analyze Airbnb customer reviews.
* Clean and preprocess review text.
* Identify English-language reviews for sentiment analysis.
* Classify reviews into Positive, Neutral, and Negative sentiments.
* Analyze the overall sentiment distribution.
* Identify the most frequently mentioned words in customer reviews.
* Analyze common words in positive and negative reviews.
* Derive meaningful business insights from customer feedback.
  
## Dataset

The project uses an Airbnb guest reviews dataset from Paris. The `comments` column was used as the primary text field for sentiment analysis.

Due to the large size of the original dataset, the raw dataset is not included in this GitHub repository. A random sample of up to 10,000 reviews was selected for analysis, and English-language reviews were retained for VADER sentiment analysis.

## Tools & Technologies

* Python
* Pandas
* NumPy
* NLTK
* VADER Sentiment Analysis
* Langdetect
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Workflow

1. Data Loading
2. Data Inspection
3. Missing Value Handling
4. Random Sampling
5. Language Detection
6. Text Preprocessing
7. VADER Sentiment Analysis
8. Sentiment Classification
9. Sentiment Distribution Analysis
10. Word Frequency Analysis
11. Positive Review Analysis
12. Negative Review Analysis
13. Data Visualization
14. Business Insights

## Key Findings

The sentiment analysis shows a strongly positive overall sentiment among the analyzed English-language reviews. Positive reviews represent the majority of the dataset, while negative reviews form a smaller proportion.

The word-frequency analysis highlights recurring themes related to accommodation, location, accessibility, cleanliness, hosts, and the overall guest experience.

## Business Insights

The positive review themes help identify aspects of the guest experience that customers value and that hosts can continue to maintain. Recurring themes in negative reviews can help identify specific areas requiring attention and improvement, supporting better guest satisfaction and service quality.

## Conclusion

The project demonstrates how Natural Language Processing and sentiment analysis can be applied to customer reviews to identify sentiment patterns, recurring themes, and actionable business insights. VADER provides an effective approach for classifying the sentiment of English-language guest reviews and understanding overall customer feedback.

## Project Structure

```text
Airbnb-Reviews-Sentiment-Analysis/
│
├── Airbnb_Reviews_Sentiment_Analysis.ipynb
├── README.md
└── reviews.csv
```

## Author

This project was developed as part of an internship project focused on data analysis and Natural Language Processing.
## Afsheen Mohammed
