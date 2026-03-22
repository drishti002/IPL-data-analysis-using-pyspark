# 🏏 IPL Data Analysis using PySpark

## 📌 Overview

This project is an end-to-end data analytics pipeline built using **PySpark** to analyze IPL (Indian Premier League) cricket data. It focuses on transforming raw ball-by-ball and match-level datasets into meaningful insights through data engineering, feature engineering, and analytical queries.

The project simulates a real-world big data workflow, leveraging distributed processing and structured data transformations.

---

## 🚀 Key Features

### 🔹 Data Engineering

* Schema definition for structured data ingestion
* Data cleaning and preprocessing
* Handling missing values and inconsistencies

### 🔹 Feature Engineering

* High-impact delivery detection (runs + wickets)
* Player categorization (batting style, experience level)
* Match-level enhancements (win margin categories, toss impact)
* Time-based features (year, month, day)

### 🔹 Advanced Analytics

* Window functions for cumulative metrics (running total runs)
* Player performance analysis
* Toss vs match outcome insights
* Venue-based scoring patterns

### 🔹 Data Processing

* Distributed processing using PySpark
* Efficient transformations using DataFrame API
* SQL-based analysis using temporary views

### 🔹 Visualization

* Conversion to Pandas for plotting
* Graphical representation of insights using Matplotlib/Seaborn

---

## Concepts Used

* PySpark DataFrames
* Window Functions
* Data Cleaning & Transformation
* Feature Engineering
* Spark SQL
* Aggregations & Grouping
* Distributed Computing

---

## 📂 Dataset

The dataset includes:

* Ball-by-ball match data
* Match details
* Player information
* Team data

(Source: IPL datasets stored on AWS S3)

---

## ⚙️ Tech Stack

* **Python**
* **PySpark**
* **AWS S3**
* **Pandas**
* **Matplotlib / Seaborn**

---

## 📊 Sample Insights

* Identification of top-performing batsmen by season
* Analysis of economical bowlers in powerplay
* Impact of toss on match outcomes
* High-scoring venues and match patterns
* Player performance in winning matches

---

## 📈 Project Workflow

1. Data Ingestion from AWS S3
2. Schema Definition
3. Data Cleaning & Preprocessing
4. Feature Engineering
5. Analytical Processing (Window Functions & SQL)
6. Visualization of Insights

---

## 🧩 Key Highlights

* Efficient use of **window functions** for cumulative analysis
* Clean and scalable data pipeline design
* Business-oriented insights generation
* Real-world big data processing approach

---

