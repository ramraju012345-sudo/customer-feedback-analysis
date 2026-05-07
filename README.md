# customer-feedback-analysis
# Customer Feedback Journey Analysis

This project analyzes customer journey using text data (customer feedback/reviews) to understand customer experience at different stages of their journey.

## Project Overview
Businesses receive large amounts of customer feedback through reviews, surveys, emails, and support interactions. This project uses Natural Language Processing (NLP) techniques to analyze customer feedback and identify:

- Customer sentiment (Positive/Negative/Neutral)
- Customer journey stages
- Frequently used words
- Customer pain points
- Overall customer experience trends

---

## Objectives
- Clean and preprocess customer feedback text
- Perform sentiment analysis
- Classify customer journey stages
- Generate visual insights using graphs
- Identify customer satisfaction patterns

---

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- NLTK
- TextBlob
- WordCloud
- Google Colab

---

## Dataset
This project uses a custom dataset containing:

- customer_id
- feedback

Example:

| customer_id | feedback |
|-------------|-----------|
| 1 | Website was easy to use but checkout was slow |
| 2 | Product quality is excellent |
| 3 | Customer support was not helpful |

---

## Project Workflow

### 1. Data Collection
Upload customer feedback dataset

### 2. Data Preprocessing
- Convert text to lowercase
- Remove punctuation
- Remove stopwords
- Clean text data

### 3. Sentiment Analysis
Classify feedback into:
- Positive
- Negative
- Neutral

### 4. Customer Journey Mapping
Feedback is categorized into stages such as:
- Awareness
- Consideration
- Purchase
- Support
- Retention

### 5. Data Visualization
Generated graphs:
- Sentiment distribution chart
- Journey stage chart
- Word frequency chart
- Word cloud
- Pie chart

---

## Results
This project helps businesses:

- Understand customer pain points
- Improve customer experience
- Increase retention
- Optimize customer journey stages

---

## Repository Structure

```bash
customer-feedback-analysis/
│
├── Customer_feedback_journey.ipynb
├── customer_feedback_dataset.csv
└── README.md
