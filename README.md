# H-M-Customer-Segmentation-for-Online-Marketing-Strategy

1. Project Overview

This project aims to perform customer segmentation using large-scale transaction data from H&M and propose data-driven online marketing strategies.

With the decline of offline store visits after COVID-19, fashion retailers needed to strengthen their online customer engagement strategies. This project analyzes customer purchasing behavior to identify meaningful customer groups and develop targeted marketing strategies.

Dataset: H&M Personalized Fashion Recommendations (Kaggle)

2. Business Problem

Due to the COVID-19 pandemic, offline store visits decreased significantly, leading to a decline in overall transactions.

To address this issue, the goal of this project is to:

Segment customers based on purchasing behavior

Identify high-value and potential customer groups

Propose targeted online marketing strategies

3. Data Description

Dataset from Kaggle:

H&M Personalized Fashion Recommendations Dataset

Key statistics:

Customers: 1.37 million

Transactions: 31.78 million

Articles: Fashion product information

Key variables used:

Customer demographic information

Transaction history

Purchase frequency

Product categories

4. Data Preprocessing

The following preprocessing steps were applied:

1️⃣ Customer and transaction datasets were merged
2️⃣ Customer-level features were generated from transaction history

Examples of features:

Purchase frequency

Product category diversity

Recency of purchase

Transaction patterns

3️⃣ Data transformation

One-hot encoding for categorical variables

Standard scaling for numerical variables

These steps enabled effective clustering for customer segmentation.

5. Customer Segmentation Modeling

Two clustering algorithms were compared:

K-means clustering

Gaussian Mixture Model (GMM)

Evaluation criteria:

cluster separation

interpretability

distribution flexibility

GMM was selected as the final model because it better captured probabilistic cluster structures and overlapping customer behaviors.

Optimal number of clusters: 7

6. Results

The model identified 7 distinct customer segments.

Key segments include:

High-Value Young Customers

high purchase frequency

strong interest in fashion

high engagement with new items

Online-Oriented Customers

frequent online purchases

responsive to digital promotions

Potential Customers (Pre-create group)

low purchase frequency

high potential for engagement

Fashion Enthusiasts

high product diversity

trend-sensitive purchasing behavior

7. Marketing Strategy

Based on customer segments, the following strategies were proposed:

1. High-value customers

early access to new collections

loyalty reward programs

2. Online-oriented customers

personalized product recommendations

targeted digital promotions

3. Potential customers

discount campaigns

onboarding promotions

4. Fashion enthusiasts

influencer marketing

fashion trend newsletters

These strategies enable data-driven targeted marketing.

8. Limitations

Several limitations exist in this analysis:

Gender information was not available, limiting demographic analysis

Due to the large dataset size, not all transaction features could be fully utilized

Some advanced behavioral features could not be generated due to computational constraints

9. My Contribution

This project was conducted as a team project.

My responsibilities included:

Implementing K-means clustering for customer segmentation

Participating in model comparison

Preparing the presentation materials (PPT)

Writing the final project report

10. What I Learned

Through this project, I gained experience in:

handling large-scale customer transaction datasets

applying unsupervised learning for customer segmentation

translating analytical results into practical marketing strategies
