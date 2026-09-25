# 🚨 Social Media Toxicity & Community Health Monitoring Dashboard using NLP

> An end-to-end Natural Language Processing, Machine Learning, Sentiment Analysis, and Power BI project for detecting toxic online comments, analyzing sentiment patterns, and monitoring community-level conversation health.

---

## 📌 Project Overview

**Social Media Toxicity & Community Health Monitoring Dashboard using NLP** is an end-to-end Data Science project developed to analyze large volumes of online comments and identify potentially toxic communication patterns.

The project combines **Natural Language Processing (NLP), Machine Learning, Sentiment Analysis, Text Analytics, and Microsoft Power BI** to transform unstructured comments into meaningful analytical insights.

The system performs:

- Text preprocessing and cleaning
- NLP-based feature extraction using TF-IDF
- Toxicity classification using Machine Learning
- Model comparison using multiple classification algorithms
- Sentiment analysis using VADER
- Toxicity category analysis
- Toxic comment word-frequency analysis
- Community-level analytical metrics
- Interactive Power BI dashboard development

The final output is an interactive dashboard that allows users to understand the overall toxicity level, sentiment distribution, toxicity categories, and other analytical patterns within the dataset.

---

# 🎯 Project Objectives

The primary objectives of this project are:

- Detect toxic and non-toxic online comments.
- Identify different categories of toxic behavior.
- Compare multiple Machine Learning classification models.
- Evaluate models using Accuracy, Precision, Recall, and F1-Score.
- Select an appropriate model for toxicity classification.
- Perform sentiment analysis on online comments.
- Analyze the relationship between toxicity and sentiment.
- Identify frequently occurring words in toxic comments.
- Create a project-defined Community Health Score.
- Build an interactive Power BI dashboard.
- Demonstrate an end-to-end Data Science and Business Intelligence workflow.

---

# 🧠 Problem Statement

Online platforms generate massive amounts of user-generated content every day. While these platforms encourage communication and discussion, they can also contain toxic, abusive, insulting, threatening, or hateful content.

Manually reviewing large volumes of comments is difficult and time-consuming.

This project addresses the problem by developing an NLP and Machine Learning pipeline that can automatically analyze comments and provide insights such as:

- Is the comment toxic?
- What type of toxicity is present?
- What is the sentiment of the comment?
- What words frequently appear in toxic comments?
- What proportion of comments are toxic?
- How does toxicity relate to sentiment?
- What does the overall analytical community health indicator look like?

---

# 💡 Proposed Solution

The proposed solution processes online comments through a complete NLP and Machine Learning pipeline.

```text
                    RAW COMMENTS
                         │
                         ▼
                DATA PREPROCESSING
                         │
                         ▼
                  NLP CLEANING
                         │
                         ▼
                 TF-IDF VECTORIZATION
                         │
                         ▼
              MACHINE LEARNING MODELS
                         │
              ┌──────────┼──────────┐
              ▼          ▼          ▼
        Logistic       Naive      Linear
       Regression      Bayes        SVM
              │          │          │
              └──────────┼──────────┘
                         ▼
                  MODEL EVALUATION
                         │
                         ▼
                 FINAL TOXICITY MODEL
                         │
              ┌──────────┴──────────┐
              ▼                     ▼
        TOXICITY ANALYSIS      SENTIMENT ANALYSIS
              │                     │
              └──────────┬──────────┘
                         ▼
                 TEXT ANALYTICS
                         │
                         ▼
              COMMUNITY METRICS
                         │
                         ▼
                 POWER BI DASHBOARD
