# Fake_News_Detection_Using_ML


## Introduction

The rise of fake news was one of the highlights of the pandemic. The dangerous effects of fake news were not only limited to viral unscientific cures of coronavirus but also incited riots and unrest, disrupting overall peace and harmony. Fake news may be a relatively new term but it is not necessarily a new phenomenon. Fake news has been around since the appearance and popularity of one-sided, partisan newspapers in the 19th century. Advances in technology and the spread of news through different types of media have increased the spread of fake news today. As such, the effects of fake news have increased exponentially in the recent past and something must be done to prevent this from continuing in the future.

We have identified three prevalent motivations for writing fake news and chosen one as the target for this project to narrow the search in a meaningful way:

1. **Influence Public Opinion**: Dating back to the 19th-century one-sided party newspapers.
2. **Clickbait for Revenue**: Utilizing fake headlines as clickbait to raise money.
3. **Satirical Writing**: A type of parody presented in a format typical of mainstream journalism, intended to be humorous and not deceptive.

This project focuses primarily on fake news defined as “fabricated content that intentionally masquerades as news coverage of actual events,” excluding satire. Our goal is to use machine learning to classify factually correct and incorrect news by studying the discrepancies between them.

## Problem Statement

Using machine learning, we aim to build a model to distinguish between factually correct and incorrect news, which will help reduce the spread of fake news. Our model is built on the Transformer architecture, making it easier to learn representations from fake news data and aiding in the early detection of fake news. Additionally, we leverage the side information (metadata) from the news content and social surroundings to improve classification. We propose a novel weak supervision paradigm for identifying news articles, which minimizes the workload of laborious labeling tasks by instantly taking labels from reliable sources and continuously updating them.

## Approach

There are different approaches one can take, such as supervised learning, unsupervised learning, or deep learning. For fake news detection, supervised learning is a common approach. In supervised learning, the model is trained on labeled data, where the true class of each article (real or fake) is known. The goal is to train a model that can accurately classify new, unseen articles as either real or fake.

## Project Implementation

### Objectives

The main objectives of this study are:
1. Collect and preprocess a dataset consisting of real and fake news articles.
2. Develop machine learning models for fake news detection using Logistic Regression, Decision Tree Classifier, and Random Forest Classifier.
3. Evaluate the performance of these models using appropriate metrics, focusing on the Confusion Matrix.
4. Provide a comparative analysis of the models to determine their effectiveness in detecting fake news.

### Data Collection and Preprocessing

1. **Data Source**: For this study, a dataset was collected from Kaggle, containing two main sources:
   - `True.csv`: A collection of verified true news articles.
   - `Fake.csv`: A collection of fabricated or fake news articles.

2. **Data Preprocessing**: 
   - Merging the two datasets.
   - Removing duplicates and irrelevant columns.
   - Cleaning and tokenizing text data.
   - Balancing the dataset to ensure an equal number of real and fake news articles.

### Data Exploration

After data preparation, the next step is to explore the data to gain insights into its characteristics. You can use various libraries like `matplotlib` and `seaborn` to explore the data and identify any patterns or trends.

### Data Preparation and Cleaning

This involves cleaning and preprocessing the data, including tasks such as removing duplicates, handling missing values, and correcting errors in the data.

### Compiler and Environment Used

**Jupyter Notebook**: An open-source web application that allows you to create and share documents containing live code, equations, visualizations, and narrative text. Uses include data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and more.

**Advantages**:
- All in one place
- Easy to share
- Language independent
- Interactive code

## Conclusion

This project is intended to be one tool that could aid humans in classifying fake news or be part of future applications that combine multiple tools to automate the process of fake news classification.

---


