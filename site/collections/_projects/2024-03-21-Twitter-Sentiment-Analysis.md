---
_schema: default
date: 2024-03-21 19:20:00 -0400
title: Twitter Sentiment Analysis
subtitle: Big Data - NLP - Data Analysis
image: /uploads/twitter.png
---
[GitHub Repo](https://github.com/SederaRas/BIG_DATA_PROJECT.git "Github Repo"){: target="_blank" rel="nofollow noopener"}

## Overview

Sentiment analysis, also known as opinion mining, is a **natural language processing** (NLP) technique used to detect and extract emotions or opinions expressed in text. The goal is to assess whether the sentiment is positive, negative, or neutral.

In this project, I chose to analyze **AI-related tweets** because artificial intelligence is a rapidly evolving and widely discussed topic. Understanding public sentiment on AI can provide valuable insights into how people perceive its impact on society, industries, and the future. Analyzing these tweets sheds light on the public’s concerns, excitement, and neutral views regarding AI’s growing role in our lives.

By leveraging Big Data platforms like **Databricks** and **AWS**, I performed sentiment analysis on AI-related tweets to extract actionable insights. The tweets were sourced from the WeCloudData public S3 bucket, and since they were not pre-labeled, **TextBlob** was used to assign sentiment labels. The labeled data was processed using **PySpark** on Databricks for sentiment analysis, with results exported to a personal S3 bucket for further exploration.

To dive deeper into the data, I utilized **Amazon Athena** to query and analyze the sentiment, and the findings were visualized using **Amazon QuickSight** in a comprehensive dashboard.

## Key Components

This project involved the following steps:

* **Data Labeling**: Sentiment labels were generated using TextBlob for the unlabeled tweets.
* **Sentiment Analysis**: Conducted using PySpark MLlib on Databricks.
* **Data Storage**: Results were exported to a personal S3 bucket on AWS.
* **Data Querying**: Amazon Athena was used to run SQL queries on the processed data.
* **Data Visualization**: Insights were visualized in an Amazon QuickSight dashboard.

![](/uploads/histo-tweetscounts-by-type-label.png "Count of tweets by type and label")

![](/uploads/wordcloud2.png "WordCloud of the tweets")

### **Findings/Results**

The analysis of AI-related tweets revealed some interesting insights into public sentiment:

* **Negative Sentiment**: Approximately **50%** of the tweets expressed negative opinions about AI, often highlighting concerns around job automation, ethical issues, and the future of human-AI interaction.
* **Positive Sentiment**: Around **30%** of the tweets were positive, showcasing excitement about AI’s potential for innovation, improving efficiency, and solving complex problems.
* **Neutral Sentiment**: Roughly **15%** of the tweets were neutral, indicating a balanced or indifferent stance on AI-related topics.

These findings highlight the mixed emotions surrounding AI, offering a deeper understanding of how people are reacting to this rapidly advancing technology.

&nbsp;

#### Skills and Tools Used

* ***NLP & Sentiment Analysis***: TextBlob, PySpark libraries
* ***Big Data & Cloud Platforms***: Databricks, AWS (EC2, S3, Amazon Athena, QuickSight)
* ***Machine Learning & Data Pipeline***