# Supply_Chain_Delay_Prediction

## Project Overview

Late deliveries are one of the most significant challenges in supply chain management, leading to increased operational costs, reduced customer satisfaction, and inefficient inventory planning.

This project develops a machine learning-based predictive system to identify orders that are likely to experience delivery delays. By leveraging historical supply chain and logistics data, the model helps businesses proactively detect high-risk shipments and make informed operational decisions.

## Business Problem

Organizations operating large-scale supply chains face substantial losses due to delayed deliveries. Traditional monitoring systems often identify delays only after they occur.

The objective of this project is to:

* Predict whether an order will be delivered late.
* Identify key factors contributing to delivery delays.
* Support data-driven logistics and operational planning.
* Improve customer satisfaction through proactive intervention.

## Dataset

The dataset contains historical supply chain records including information related to:

* Product Categories
* Customer Segments
* Market Regions
* Shipping Modes
* Order Information
* Delivery Status
* Sales and Profit Metrics

### Target Variable

**Delayed Delivery**

* 1 = Late Delivery
* 0 = On-Time/Early Delivery

## Project Workflow

### 1. Data Understanding

Initial exploration of the dataset including:

* Dataset dimensions
* Variable types
* Summary statistics
* Missing value analysis

### 2. Data Preprocessing

Data preparation steps included:

* Duplicate column handling
* Frequency Encoding for high-cardinality categorical variables
* Label Encoding for categorical variables
* Feature scaling using StandardScaler
* Target variable creation

### 3. Exploratory Data Analysis (EDA)

Exploratory analysis was conducted to understand:

* Distribution of delivery outcomes
* Shipping mode performance
* Regional delivery patterns
* Relationships between variables
* Correlation structure of numerical features

### 4. Feature Engineering

Additional transformations were performed to improve model performance and ensure compatibility with machine learning algorithms.

### 5. Model Development

Multiple classification algorithms were implemented and compared:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Gaussian Naive Bayes

### 6. Hyperparameter Optimization

Grid Search Cross Validation (GridSearchCV) was used to optimize Decision Tree parameters and improve predictive performance.

### 7. Model Evaluation

Models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* ROC-AUC Analysis

### 8. Feature Importance Analysis

Random Forest feature importance was used to identify the most influential predictors of delivery delays.

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

### Machine Learning Techniques

* Classification Models
* Hyperparameter Tuning
* Feature Engineering
* Feature Importance Analysis

## Key Insights

The analysis revealed that:

* Shipping mode significantly influences delivery performance.
* Certain regions are more susceptible to delivery delays.
* Order and logistics characteristics are strong predictors of late deliveries.
* Machine learning models can effectively identify high-risk shipments before dispatch.

## Business Impact

This solution can help organizations:

* Reduce operational inefficiencies.
* Improve delivery performance.
* Enhance customer satisfaction.
* Optimize logistics planning.
* Enable proactive supply chain risk management.
