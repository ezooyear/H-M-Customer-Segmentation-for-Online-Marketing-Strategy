# H&M Customer Segmentation
H-M-Customer-Segmentation-for-Online-Marketing-Strategy

## 1. Project Overview

This project aims to perform **customer segmentation using large-scale transaction data from H&M** and propose **data-driven online marketing strategies**.

With the decline of offline store visits after COVID-19, fashion retailers needed to strengthen their **online customer engagement strategies**.  
This project analyzes customer purchasing behavior to identify meaningful customer groups and develop **targeted marketing strategies**.

**Dataset:** H&M Personalized Fashion Recommendations (Kaggle)

---

## 2. Business Problem

Due to the **COVID-19 pandemic**, offline store visits decreased significantly, leading to a decline in overall transactions.

To address this issue, the goal of this project is to:

- Segment customers based on **purchasing behavior**
- Identify **high-value and potential customer groups**
- Propose **targeted online marketing strategies**

---

## 3. Data Description

Dataset from Kaggle:

**H&M Personalized Fashion Recommendations Dataset**

### Key Statistics

- **Customers:** 1.37 million  
- **Transactions:** 31.78 million  
- **Articles:** Fashion product information  

### Key Variables Used

- Customer demographic information  
- Transaction history  
- Purchase frequency  
- Product categories  

---

## 4. Data Preprocessing

The following preprocessing steps were applied:

### 1. Data Integration

- Customer dataset and transaction dataset were merged.

### 2. Feature Engineering

Customer-level behavioral features were generated from transaction history.

Examples of features:

- **Purchase frequency**
- **Product category diversity**
- **Recency of purchase**
- **Transaction patterns**

### 3. Data Transformation

- **One-hot encoding** for categorical variables  
- **Standard scaling** for numerical variables  

These preprocessing steps enabled effective clustering for **customer segmentation**.

---

## 5. Customer Segmentation Modeling

Two clustering algorithms were compared:

- **K-means Clustering**
- **Gaussian Mixture Model (GMM)**

### Evaluation Criteria

- Cluster separation  
- Interpretability  
- Distribution flexibility  

After comparison, **GMM was selected as the final model** because it better captured **probabilistic cluster structures and overlapping customer behaviors**.

**Optimal number of clusters:** **7**

---

## 6. Results

The model identified **7 distinct customer segments**.

### Key Segments

#### 1. High-Value Young Customers
- High purchase frequency  
- Strong interest in fashion  
- High engagement with new items  

#### 2. Online-Oriented Customers
- Frequent online purchases  
- Responsive to digital promotions  

#### 3. Potential Customers (Pre-create Group)
- Low purchase frequency  
- High potential for engagement  

#### 4. Fashion Enthusiasts
- High product diversity  
- Trend-sensitive purchasing behavior  

---

## 7. Marketing Strategy

Based on customer segments, the following **data-driven marketing strategies** were proposed.

### 1. High-Value Customers
- Early access to new collections  
- Loyalty reward programs  

### 2. Online-Oriented Customers
- Personalized product recommendations  
- Targeted digital promotions  

### 3. Potential Customers
- Discount campaigns  
- Onboarding promotions  

### 4. Fashion Enthusiasts
- Influencer marketing  
- Fashion trend newsletters  

These strategies enable **data-driven targeted marketing**.

---

## 8. Limitations

Several limitations exist in this analysis:

- **Gender information was not available**, limiting demographic analysis  
- Due to the **large dataset size**, not all transaction features could be fully utilized  
- Some advanced behavioral features could not be generated due to **computational constraints**

---

## 9. My Contribution

This project was conducted as a **team project**.

My responsibilities included:

- Implementing **K-means clustering for customer segmentation**
- Participating in **model comparison**
- Preparing the **presentation materials (PPT)**
- Writing the **final project report**

---

## 10. What I Learned

Through this project, I gained experience in:

- Handling **large-scale customer transaction datasets**
- Applying **unsupervised learning for customer segmentation**
- Translating analytical results into **practical marketing strategies**
