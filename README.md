# Olist_ETL
End-to-end e-commerce analytics project using the Olist dataset. Built a full ETL pipeline with Apache Spark, PostgreSQL, and Power BI to process large-scale data and apply machine learning for seller segmentation.

Dataset Link : https://www.kaggle.com/olistbr/brazilian-ecommerce

The data in this project comes from the Brazilian E-Commerce Public Dataset by Olist, which contains approximately 100,000 orders placed between 2016 and 2018 on multiple marketplaces in Brazil. 
These transactions include a variety of attributes such as order status, pricing, freight and payment details, customer and seller geography, product characteristics and post-purchase reviews. 
Also included is a geolocation component linking Brazilian zip-code prefixes to latitude/longitude coordinates, enabling spatial analysis of customer-seller interactions. 
This repository applies this rich dataset to build analytics and machine-learning solutions covering areas such as customer segmentation, recommendation systems, sales forecasting, product and delivery performance, and feature engineering.

## Problem Statement

In the evolving e-commerce landscape, companies face significant challenges when working with large-scale marketplace data. First, the ***data-processing complexity*** is substantial: multiple interconnected tables, time-based relationships, and data quality issues mean that standard batch tools often struggle to keep up. Second, seller segmentation remains a major hurdle: simple performance metrics don’t capture the nuanced differences between seller types, making it hard to target strategic improvements. Third, modern businesses require near-real-time insights — integrating complex data processing workflows with user-friendly dashboards and operational decision-support is technically and operationally demanding. This project tackles all three: building a scalable pipeline, applying advanced segmentation techniques, and delivering meaningful business insights in a timely manner.
