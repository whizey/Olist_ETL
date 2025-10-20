# Olist_ETL
End-to-end e-commerce analytics project using the Olist dataset. Built a full ETL pipeline with Apache Spark, PostgreSQL, and Power BI to process large-scale data and apply machine learning for seller segmentation.

Dataset Link : https://www.kaggle.com/olistbr/brazilian-ecommerce

The data in this project comes from the Brazilian E-Commerce Public Dataset by Olist, which contains approximately 100,000 orders placed between 2016 and 2018 on multiple marketplaces in Brazil. 
These transactions include a variety of attributes such as order status, pricing, freight and payment details, customer and seller geography, product characteristics and post-purchase reviews. 
Also included is a geolocation component linking Brazilian zip-code prefixes to latitude/longitude coordinates, enabling spatial analysis of customer-seller interactions. 
This repository applies this rich dataset to build analytics and machine-learning solutions covering areas such as customer segmentation, recommendation systems, sales forecasting, product and delivery performance, and feature engineering.

## Problem Statement

In the evolving e-commerce landscape, companies face significant challenges when working with large-scale marketplace data. First, the ***data-processing complexity*** is substantial: multiple interconnected tables, time-based relationships, and data quality issues mean that standard batch tools often struggle to keep up. Second, ***seller segmentation*** remains a major hurdle: simple performance metrics don’t capture the nuanced differences between seller types, making it hard to target strategic improvements. Third, modern businesses require near-real-time insights — integrating complex data processing workflows with user-friendly dashboards and operational decision-support is technically and operationally demanding. This project tackles all three: building a scalable pipeline, applying advanced segmentation techniques, and delivering meaningful business insights in a timely manner.

## Objective

* Develop a scalable ETL pipeline for large-scale e-commerce data.
* Build advanced clustering models to segment sellers into distinct profiles.
* Analyze Brazilian e-commerce trends to derive actionable business insights.
* Define and document best practices for e-commerce analytics projects.

## Dataset Characteristics and Structure
The Olist dataset is one of the most detailed public e-commerce datasets out there,
covering nearly 100,000 orders from 2016 to 2018. It includes nine interconnected tables
that capture diﬀerent parts of the e-commerce process:

***Orders***: The main table with order IDs, customer details, timestamps, and status
updates, acting as the key to link other data.

***Order Items***: Details on products in each order, including prices, shipping costs,
and seller info.

***Products***: Product catalog data like categories, sizes, and weights.

***Sellers***: Geographic and operational details about marketplace sellers.

***Customers***: Customer location and unique IDs.

***Payments***: Payment method details, installment plans, and transaction amounts.

***Reviews***: Customer satisfaction scores and review text.

***Geolocation***: Precise coordinates for Brazilian postal codes.

This multi-table setup mirrors the complexity of real-world e-commerce and opens
the door for advanced analysis that looks at how diﬀerent parts of the business interact.

## Architecture of Data Schema

<img width="839" height="492" alt="Screenshot 2025-10-20 at 11 18 18 AM" src="https://github.com/user-attachments/assets/48b7adbb-b571-4832-8dff-dc24acbb8446" />

## Pipeline

***Data Wrangling*** – The process of cleaning and unifying messy and complex datasets so that they become accessible and ready for analysis.

***Exploratory Data Analysis (EDA)*** – A phase where a variety of techniques (mostly graphical) are applied to understand data structure, distributions, relationships and guide further modelling.

***Modelling*** – Training a machine learning algorithm using features derived from the data to predict target outcomes, tuning it for the business need, and validating the model on hold-out data.

***Model Evaluation*** – After splitting the data into training and test sets, the process of applying the model to the test data, measuring performance, and ensuring it meets the business requirements.

***Dockerising*** – Converting the application or analytics workflow into a containerised format (e.g., using Docker) so that it can run reliably across different environments.

***Deployment*** – Integrating the trained model or analytics system into a production-grade environment so it can take inputs and deliver outputs that support actual business decision-making.

## Power Bi Implementation
<img width="787" height="452" alt="Screenshot 2025-10-20 at 11 15 38 AM" src="https://github.com/user-attachments/assets/7435bddc-2bfd-4a66-b646-dbd9b08d4298" />
PowerBI Dashboard showing comprehensive e-commerce analytics and key performance indicators

## Project Report
[Modern E-commerce Analytics: Crafting a Full ETL Pipeline and Machine Learning System for Brazilian Marketplace Data.pdf](https://github.com/user-attachments/files/22997772/Modern.E-commerce.Analytics.Crafting.a.Full.ETL.Pipeline.and.Machine.Learning.System.for.Brazilian.Marketplace.Data.pdf)
