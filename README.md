# Customer Lifetime Value Prediction & LTV Segmentation

### Objective: 
We have to predict the customer's lifetime value and segment the customers based on their LTV so that we can provide this information to the marketing team for the campaign & CPA optimization.

### Introduction:
The dataset which we are going to use in this problem has taken from the UCI Machine Learning Repository. This is a transactional data set which contains all the actual transactions for a UK-based and registered ecommerce online retail store. The company mainly sells unique all-occasion gifts. This dataset has several features which includes the Invoice Number, Stock Code, Product Description, Product Quantity, Invoice Date, Unit Price, Customer ID, etc.

Before starting with the model, let's first understand what is Customer Lifetime Value.

![Customer Lifetime Value Prediction](https://neilpatel.com/wp-content/uploads/2018/05/facebook-lifetime-value.jpg)

### Abstract

**What is Customer Lifetime Value?**

[Customer lifetime value](https://en.wikipedia.org/wiki/Customer_lifetime_value) (CLV) is one of the key stats likely to be tracked as part of a customer experience program. CLV is a measurement of how valuable a customer is to your company with an unlimited time span as opposed to just the first purchase. This metric helps you understand a reasonable cost per acquisition.
CLV is the total worth to a business of a customer over the whole period of their relationship. It’s an important metric as it costs less to keep existing customers than it does to acquire new ones, so increasing the value of your existing customers is a great way to drive growth.

**Challenges -** 
Some companies don’t attempt to measure CLV, citing the challenges of segregated teams, inadequate systems, and untargeted marketing.

**Why is it important to track customer lifetime value?**

CLTV tell marketers, how much revenue they can expect from one customer over the course of the business relationship. The longer a customer continues to purchase from a company, the greater their lifetime value becomes.

To calculate the customer lifetime value, there are several methods available on the internet which you can google but here I am going to share with you the model which I have used and the reason behind choosing that specific model.

To create the model first we have to understand the course of business or in short business context and its customer's.

There are basically two types of business context which I am going to discuss below regards to the relationship and purchase opportunities.

**a) Contractual -** Contractual business refers to the business where there is a definite time when the customer is going to churn or we can say we know when the customer is going to be dropped. This type of customer relationship known as contractual and the customers called the subscription customers. For Ex - Hotstar, Netflix, Amazon Prime Subscription

**b) Non-Contractual -**  In the non-contractual world, customers do go away, but they do so silently; they have no need to tell us they are leaving. This makes for a much trickier CLV calculation. For Ex- Retail/E-Commerce

![Business Context](https://2zzm8x3dsugfsdli13ukukea-wpengine.netdna-ssl.com/wp-content/uploads/hardie_non_contract_continuous.png)

**Purchase Opportunities Types:**

**a) Continuous -** It refers the purchase opportunites when there is continuous purchases done by the customers.

**b) Discrete -** Under discrete, the purchase happened on a specific time period. For Ex- Subscription Plan

So based on the above, we can identify the business context and choose method which is best suited for the case.

### Purpose of the research

Following the problem and motivation described above, the purpose of this study is formulated. The study aims at investigating possible methods with context to the non-contractual-continuous business for estimation of potential revenue (CLV) generated by a certain group of active customers. To perform this estimation, the probabilistic models (Pareto-NBD, BG-NBD, MBG-NBD & Gamma Gamma) has been applied to the case study in the industry. Customer segmentation by means of unsupervised machine learning was also performed in order to show an efficient tool for strategy planning.

***Steps Involved in this Project:*** Data Importing | Data Cleaning | Exploratory Data Analysis | Feature Engineering/Extraction | Cross Validation | Different Predictive Models Building | LTV Based Customer Segmentation | Model Evaluation | Model Deployment

***Libraries Used***

a) Scikit Learn
b) Lifetimes
c) Plotly, Matplotlib, Seaborn, Altair
d) XLRD
e) Numpy
f) Pandas
g) Datetime
h) Math
i) Pickle
j) Warnings
