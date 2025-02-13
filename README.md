# Data Science: A Guided Journey

This project is a curated collection of data science assignments, restructured and revisited with a deeper understanding. The goal is not just to redo old assignments but to transform them into well-documented resources that provide a structured learning path for aspiring data scientists.

## Scope
Data science is not just about knowing algorithms but about developing a strong rationale—understanding why we choose specific techniques, how to handle messy real-world data, and how to derive meaningful insights. This repository is designed to:

- **Revisit fundamental concepts with a fresh perspective**
- **Provide structured solutions with explanations**
- **Offer well-organized code for beginners to learn from**
- **Share best practices for handling unstructured and messy data**

---

### **Data Preparation & Cleaning**  
- [Week 01](#week-01-epileptic-seizure-data-preparation)  
- [Week 02](#week-02-glucose-level-data)

`*More modules will be added as the repository evolves.* `


## Week 01 : Epileptic Seizure Data Preparation


## Overview
As a Data Scientist, you often have lots of data at your disposal. Unfortunately, data from real-life cases is often not nicely structured. We need to manipulate the unstructured and/or messy data into a structured or clean form.

## Objective
Data preparation involves several key steps:
- **Dropping unnecessary rows and columns**: Some data points might not be needed for analysis, or they may contain too many missing values.
- **Relabeling columns**: Ensuring column names are meaningful and correctly formatted.
- **Reformatting characters into numerical values**: Converting categorical or text data into numerical representations.
- **Combining data from multiple sources**: Merging datasets to enrich the available information.

**Cleaning and manipulating data into a structured form is crucial for effective analysis and modeling.**

## Keywords
- **Data wrangling** with pandas, NumPy, yaml.
- **Data visualization** matplotlib, Bokeh.
- **Preprocessing EEG (electroencephalogram) data** into an appropriate format for statistical and visual analysis.

---

## Week 02 : Glucose Level Data

## Overview
Missing data occurs commonly in many data applications. Especially wearable sensor devices encounter measurement errors resulting in missing data. Although pandas can handle missing data, for instance, to exclude missing data in the descriptive analysis, we might decide to reshape our data to improve quality. We might consider excluding certain rows, columns, or decide to impute our data if we take an argumentative approach.

## Objectives
We will work with sensor data of a project. The data is timeseries related but a lot of sensor errors occurred.
- **First, we inspect the quality of the data.**
- **Then, we will work with imputation, interpolation, and smoothing techniques to overcome this issue of error readings.**
- **Finally, we plot the data. Visualization is a method to translate data into information.**

## Keywords
**data loading, data inspection, data exploration, data cleaning, impute data, missing data, timeseries, pandas, visualization, interactive plots, overflow/underflow error**