
# Sentiment Analysis of American Airlines Passengers Reviews

**Author:** Anani A. Assoutovi  
**Affiliation:** Independent Researcher / Data Scientist  
**Email:** booking.helices4s@icloud.com  
**LinkedIn:** www.linkedin.com/in/ananiassoutovi  
**Date:** May 12, 2025  

---

## Abstract

This research investigates passenger sentiments toward American Airlines based on textual reviews. The goal is to extract and classify the emotional tone of each review using TextBlob for sentiment analysis. The insights are intended to help understand customer satisfaction trends, areas for service improvement, and general public perception.

---

## 1. Introduction

With the aviation industry being highly competitive, customer feedback becomes a vital asset for service improvement. This study focuses on analyzing 5,610 textual reviews from American Airlines passengers. The primary objective is to classify these reviews into sentiment categories—Positive, Negative, and Neutral—and visualize the sentiment landscape using word clouds and bar charts.

---

## 2. Dataset

- **Size**: 5,610 entries
- **Column**: `reviews` (free-text feedback from passengers)
- **Source**: Customer feedback collected from American Airlines-related reviews

---

## 3. Methodology

### 3.1 Text Preprocessing

Each review was cleaned by:
- Removing special characters
- Converting text to lowercase
- Stripping extra whitespace

### 3.2 Sentiment Scoring

Using the **TextBlob** library:
- **Polarity** score ranges from -1.0 (very negative) to +1.0 (very positive)
- **Subjectivity** score ranges from 0 (objective) to 1 (subjective)

### 3.3 Sentiment Classification

Based on polarity:
- **Positive**: polarity > 0
- **Neutral**: polarity = 0
- **Negative**: polarity < 0

### 3.4 Visualizations

- **Bar Plot**: Distribution of sentiment categories
- **Word Clouds**: Top words for positive and negative reviews

---

## 4. Findings

- **Sentiment Distribution** showed a higher frequency of negative reviews compared to positive ones.
- **Word Cloud** insights:
  - **Positive Reviews** commonly included: *great*, *friendly*, *excellent*, *comfortable*.
  - **Negative Reviews** frequently used: *delay*, *rude*, *worst*, *unhelpful*.
- The prevalence of negative sentiments signals dissatisfaction with delays and customer service.

---

## 5. Conclusion

The analysis highlights key areas of concern and appreciation from customers. While some passengers praise the airline's crew and comfort, many express frustration with delays and support quality. These insights can inform customer experience improvements and brand perception strategies.

---

## 6. Future Work

- Apply advanced models like VADER or BERT for sentiment analysis
- Perform topic modeling to cluster feedback themes
- Monitor sentiment trends over time for operational decision-making

---

## References

- TextBlob Library: https://textblob.readthedocs.io
- Data Visualization: Matplotlib, WordCloud
- Data Processing: pandas, re, nltk
