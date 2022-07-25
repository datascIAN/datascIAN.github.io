---
layout: post
title: "Unicorn Startups"
subtitle: "Exploratory Data Analysis"
background: '/img/posts/unicorn-startups/unicorn1.jpg'
---

## Description
"Unicorn" is a term used to describe a privately held startup company with a value of over $1 billion. This project is an exploration of the a dataset on venture capital unicorns. This analysis can help us get some insights on these unicorns.

## Objectives
- Inspect the dataset.
- Based on the inspection, come up with questions that can be answered with the dataset.
- Extract information from the dataset with these questions in mind. 

## Tools
<p align="center">
  <img width="30%" height="30%" src="/img/posts/unicorn-startups/python.png" />
  <img width="30%" height="30%" src="/img/posts/unicorn-startups/numpy.png" />
  <img width="30%" height="30%" src="/img/posts/unicorn-startups/pandas.png" />
  <img width="30%" height="30%" src="/img/posts/unicorn-startups/matplotlib.png" />
  <img width="30%" height="30%" src="/img/posts/unicorn-startups/seaborn.png" />
</p>
Python was used for this project. The following libraries were utilized:  
- Numpy
- Pandas
- Matplotlib
- seaborn

## Questions
1. Top 20 companies with the largest valuations
2. Top 10 countries with the most number of unicorn startups
3. Countries with the highest total valuation of unicorns.
4. Top countries with highest average valuation of unicorns.
5. Top industries with most startups
6. Top industries with the highest total valuation of unicorns.
7. Top investors with most startups
8. Number of startups per year.
9. Startups per industry per year.
10. Startups per country per year.

## The Data
The dataset was taken from [Kaggle.com](https://www.kaggle.com/datasets/ramjasmaurya/unicorn-startups). There are 936 companies included in this dataset with 8 columns. The 8th column is a list of major investors for each company. The contents of this column was expanded into 4 columns for each major investor if applicable. 

## 1. Top 20 companies with the largest valuations.
<p align="center">
  <img width="100%" height="100%" src="/img/posts/unicorn-startups/q1.jpg" />
</p>
Bytedance from the artificial intelligence industry has the highest valuation at $140 billion. It is followed by SpaceX at $100.3 billion and Stripe at $95 billion. Of the top 20 unicorns with the highest valuations, 7 of them come from Fintech industry.

## 2. Top 10 countries with the most number of unicorn startups.
<p align="center">
  <img width="100%" height="100%" src="/img/posts/unicorn-startups/q2.jpg" />
</p>
The United States has the most number of unicorns at 478. A distant second is China with 169. These countries are also the top 2 largest economies in the world. India has the 3rd highest number of unicorns with 51 companies. 

## 3. Countries with the highest total valuation of unicorns.
<p align="center">
  <img width="100%" height="100%" src="/img/posts/unicorn-startups/q3.jpg" />
</p>
The united states having the most number of unicorns also has the highest total valuation of unicorns at $1,605 billion. It is followed by China with a total valuation of unicorns at $569 billion. The United Kingdom beats India for 3rd place with total valuation of $150 billion even though India has a lot more unicorns that the United Kingdom.

## 4. Top countries with highest average valuation of unicorns.
<p align="center">
  <img width="100%" height="100%" src="/img/posts/unicorn-startups/q4.jpg" />
</p>
Sweden has the highest average valuation of unicorns with $14.52 billion. It is followed by Australia with $8.43 billion and Hong Kong with $5.92 billion. 

## 5. Top industries with most unicorn startups.
<p align="center">
  <img width="100%" height="100%" src="/img/posts/unicorn-startups/q5.jpg" />
</p>
Fintech has the most number of unicorn startups with 191. It is followed by Internet software & services with 167. E-commerce & direct-to-consumer follows with 102. 

## 6. Top industries with the highest total valuation of unicorns.
<p align="center">
  <img width="100%" height="100%" src="/img/posts/unicorn-startups/q6.jpg" />
</p>
With Fintech having the most number of unicorn startups, it also has the highest total valuation of unicorns at $744 billion. Internet software & services still follows with the second highest total valuation of unicorns at $483 billion. Artificial intelligence follows with a total valuation of $312 billion. 

## 7. Top investors invested with most number of startups
<p align="center">
  <img width="100%" height="100%" src="/img/posts/unicorn-startups/q7.jpg" />
</p>
Accel, an American venture capital firm, is invested in the most number of unicorn startups with 49. It is followed by Sequioa Capital China which is invested in 47 unicorn startups. Tiger Global Management follows with investments in 42 unicorn startups. 

## 8. Number of startups per year.
<p align="center">
  <img width="100%" height="100%" src="/img/posts/unicorn-startups/q8.jpg" />
</p>
The graph shows that the number of unicorn startups has grown over the years. In 2021, there were more new unicorn startups than any other year. 

## 9. Startups per industry per year.
<p align="center">
  <img width="100%" height="100%" src="/img/posts/unicorn-startups/q9.jpg" />
</p>
In 2022, Fintech had the most number of new unicorn startups. It is followed by Internet software & services industry. E-commerce & direct-to-consumer also had a lot of new unicorn startups in 2021. 

## 10. Startups per country per year. (Only the top 10 countries with the most number of startups)
<p align="center">
  <img width="100%" height="100%" src="/img/posts/unicorn-startups/q10.jpg" />
</p>
The United States, which has the most number of unicorn startups, had the most number of new unicorn startups over the years. It had around 280 in 2021 alone. It is followed by China and India.

---
**The project can be accessed on GitHub through this [link](https://github.com/datascian/Unicorn-Startups-EDA).**