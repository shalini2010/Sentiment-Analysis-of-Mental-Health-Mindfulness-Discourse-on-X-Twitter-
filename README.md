# Sentiment Analysis of Mental Health & Mindfulness Discourse on X (Twitter)

![Python](https://img.shields.io/badge/Python-3.9-blue)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)


## Project Overview

Social media platforms like **X (formerly Twitter)** have become important spaces where individuals discuss mental health, mindfulness, stress, and emotional well-being. Understanding the sentiment and themes within these conversations can provide valuable insights for researchers, policymakers, and wellness organizations.

This project performs **Natural Language Processing (NLP) and Sentiment Analysis** on tweets related to **mental health and mindfulness topics**. Using Python-based tools, the project collects tweets through the Twitter API, processes and cleans textual data, analyzes sentiment polarity, and identifies recurring discussion themes using topic modeling.

The objective is to demonstrate how **social media data can be leveraged to analyze public perception and emotional trends around mental health awareness.**

## Project Objectives

- Collect tweets related to **mental health and mindfulness topics**
- Perform **text preprocessing and cleaning**
- Conduct **sentiment analysis** on tweets
- Identify **frequent keywords and themes**
- Apply **topic modeling** to uncover discussion patterns
- Visualize insights through **data visualizations**

## Dataset

Tweets were collected using the **Twitter API via Tweepy** based on keywords related to mental health and mindfulness.

### Keywords Used

- mindfulness
- meditation
- mental health
- anxiety
- depression
- self care

### Data Fields

Each tweet includes:

- Tweet text
- Timestamp
- Tweet metadata


## Tech Stack

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Tweepy
- NLTK
- Scikit-learn

### NLP Techniques

- Text preprocessing
- Stopword removal
- Tokenization
- Sentiment analysis (VADER)
- Topic modeling (LDA)


## Project Workflow

### 1. Data Collection
Tweets were collected using **Twitter API and Tweepy** with relevant mental health keywords.

### 2. Data Preprocessing

Text data was cleaned using the following steps:

- Removing URLs
- Removing mentions and hashtags
- Removing punctuation and special characters
- Converting text to lowercase
- Removing stopwords

### 3. Exploratory Data Analysis

EDA was performed to explore the structure and trends in the dataset:

- Tweet frequency analysis
- Keyword frequency distribution
- Temporal tweet trends

### 4. Sentiment Analysis

The **VADER Sentiment Analyzer from NLTK** was used to classify tweets into:

- Positive sentiment
- Neutral sentiment
- Negative sentiment

This helps measure the **overall emotional tone of mental health discussions.**

### 5. Topic Modeling

**Latent Dirichlet Allocation (LDA)** was applied to identify underlying discussion themes within the tweets.

Example topics discovered:

- Mindfulness and meditation practices
- Anxiety and stress discussions
- Emotional well-being
- Self-care routines

## Visualizations

The project includes several visualizations such as:

- Word frequency charts
- Sentiment distribution graphs
- Keyword trend analysis

Example outputs may include:

- Word clouds of mental health discussions
- Sentiment distribution across tweets
- Topic modeling keyword clusters

*(Neet to add screenshots of charts after intitial readme commit)*


## Key Insights

- A large portion of tweets related to mindfulness contain **positive sentiment**, reflecting supportive community discussions.
- Many conversations revolve around **stress management and coping strategies.**
- Keywords like **mindfulness, meditation, anxiety, and self-care** appear frequently in discussions.
- Topic modeling reveals recurring themes related to **emotional health, personal well-being, and mental health awareness.**


## Applications

This type of analysis can be useful for:

- Mental health research
- Public health monitoring
- Social media sentiment tracking
- Wellness industry insights
- Policy research on mental health awareness


## Future Improvements

Potential extensions for this project include:

- Implementing **BERT-based sentiment analysis**
- Real-time tweet streaming analysis
- Advanced topic modeling with **BERTopic**
- Building an **interactive dashboard using Tableau or Power BI**
- Detecting **mental health risk signals using machine learning models**


## Author

**Shalini Patel**

MS in Data Analytics  
Aspiring **Data Scientist / Data Analyst**


## Skills Demonstrated

- Natural Language Processing (NLP)
- Sentiment Analysis
- Social Media Data Mining
- Data Visualization
- Python for Data Science
