# Airbnb Reviews Sentiment Analysis

## Project Overview

This project analyzes Airbnb guest reviews from Paris using Natural Language Processing (NLP) techniques. The objective is to identify the sentiment expressed in customer reviews and extract frequently mentioned topics from positive and negative feedback.

VADER sentiment analysis is used to classify reviews into Positive, Neutral, and Negative categories.

## Objectives

* Analyze Airbnb customer reviews.
* Clean and preprocess textual review data.
* Identify English-language reviews for sentiment analysis.
* Classify reviews as Positive, Neutral, or Negative.
* Analyze the overall sentiment distribution.
* Identify frequently mentioned words in customer reviews.
* Analyze common words in positive and negative reviews.
* Generate meaningful business insights from customer feedback.

## Dataset

The dataset contains Airbnb guest reviews from listings in Paris. The main text field used for analysis is the `comments` column.

The dataset contains multilingual reviews. A random sample of up to 10,000 reviews was selected for analysis, and English-language reviews were retained for VADER sentiment analysis.

> **Note:** If the dataset is not included in this repository due to redistribution restrictions, place the required `reviews.csv` file in the project directory before running the notebook.

## Technologies Used

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

1. Load the dataset
2. Inspect the data
3. Handle missing review text
4. Select a random sample of reviews
5. Detect review language
6. Retain English-language reviews
7. Preprocess review text
8. Calculate VADER sentiment scores
9. Classify reviews into sentiment categories
10. Analyze sentiment distribution
11. Identify common words
12. Analyze positive and negative review themes
13. Visualize the results
14. Derive observations and business insights
15. Present the final findings

## Key Findings

* The analyzed English-language reviews show a strongly positive overall sentiment.
* Positive reviews represent the vast majority of the analyzed sample.
* Frequently mentioned words highlight important aspects of the guest experience.
* Positive review themes reveal aspects that guests commonly value.
* Negative review themes highlight areas that may require attention and improvement.

## Project Structure

```text
Airbnb-Reviews-Sentiment-Analysis/
│
├── Airbnb_Reviews_Sentiment_Analysis.ipynb
├── README.md
└── reviews.csv
```

## How to Run the Project

1. Clone this repository.
2. Install the required Python libraries.
3. Place `reviews.csv` in the project directory if it is not included.
4. Open the Jupyter Notebook.
5. Run the notebook cells from beginning to end.

## Installation

Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn nltk langdetect jupyter
```

The notebook automatically downloads the required NLTK resources for VADER and stopword processing.

## Author

This project was developed as part of an internship project focused on data analysis and Natural Language Processing.
Afsheen Mohammed
