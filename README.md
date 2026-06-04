# 🍽️ Zomato Bangalore Restaurant Analytics

An end-to-end Exploratory Data Analysis (EDA) project on Bangalore's restaurant ecosystem using the Zomato dataset. This project focuses on uncovering customer preferences, restaurant market trends, cuisine demand, pricing patterns, and factors influencing restaurant ratings through data cleaning, visualization, and business-driven insights.

## 📖 Project Overview

The restaurant industry generates massive amounts of customer and operational data. Analyzing this data helps businesses understand market demand, customer behavior, and competitive positioning.

In this project, I analyzed the Bangalore restaurant dataset from Zomato to answer key business questions related to:

- Restaurant distribution across Bangalore
- Customer ratings and engagement
- Online ordering trends
- Pricing strategies
- Cuisine popularity
- Restaurant category performance

The objective was to transform raw restaurant data into actionable business insights using Python-based data analytics techniques.

## 🎯 Business Objectives

This analysis aims to answer the following questions:

- Which areas of Bangalore have the highest concentration of restaurants?
- Does online ordering influence customer engagement and popularity?
- How does restaurant pricing impact customer ratings?
- Which cuisines dominate Bangalore's restaurant market?
- Which restaurant categories receive the highest customer satisfaction?

## 🛠️ Tech Stack

| Category | Tools |
|-----------|---------|
| Programming Language | Python |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Development Environment | Jupyter Notebook |


## 📂 Dataset Information

**Dataset:** Zomato Bangalore Restaurant Dataset

### Features Used

| Feature | Description |
|----------|-------------|
| Name | Restaurant Name |
| Location | Area within Bangalore |
| Cuisines | Cuisine types served |
| Rate | Customer rating |
| Votes | Number of customer votes |
| Online Order | Online ordering availability |
| Listed In (Type) | Restaurant category |
| Approx Cost (For Two People) | Average dining cost |


## 🔄 Data Preprocessing

The raw dataset contained missing values, inconsistent formats, and redundant columns.

### Data Cleaning Steps

- Removed irrelevant columns
- Handled missing values
- Removed duplicate records
- Converted ratings into numerical format
- Standardized cost values
- Processed cuisine-related fields
- Prepared data for visualization and analysis

### Example Transformations

**Ratings**

```python
4.1/5 → 4.1
```

**Cost**

```python
1,200 → 1200
```

## 📊 Exploratory Data Analysis

### 1️⃣ Restaurant Distribution by Location

Analyzed the number of restaurants across Bangalore locations to identify major food hubs.

#### Key Insights

- BTM Layout emerged as one of the most restaurant-dense locations.
- Koramangala and HSR Layout also showed significant restaurant activity.
- Areas with large student and IT populations attracted more restaurants.


### 2️⃣ Online Ordering Analysis

Investigated whether online ordering impacts restaurant popularity.

#### Key Insights

- Restaurants offering online ordering generally receive more customer votes.
- Online ordering increases visibility and customer reach.
- Higher engagement does not necessarily translate to higher ratings.

#### Business Impact

Restaurants can improve customer acquisition by adopting online ordering platforms.


### 3️⃣ Cost vs Rating Analysis

Studied the relationship between restaurant pricing and customer satisfaction.

#### Key Insights

- No strong correlation exists between pricing and ratings.
- Mid-range restaurants often achieve ratings comparable to premium restaurants.
- Customer experience appears more influential than pricing.

#### Business Impact

Higher prices alone do not guarantee customer satisfaction.

### 4️⃣ Cuisine Popularity Analysis

Analyzed cuisine trends and market demand across Bangalore.

#### Most Popular Cuisines

- North Indian
- Chinese
- South Indian
- Fast Food
- Biryani

#### Key Insights

- North Indian cuisine dominates the market.
- Specialized cuisines often achieve higher average ratings.
- Diverse cuisine offerings help restaurants attract wider audiences.


### 5️⃣ Restaurant Category Analysis

Compared different restaurant categories using customer ratings and engagement.

#### Categories Analyzed

- Delivery
- Dine-Out
- Cafes
- Buffet
- Fine Dining

#### Key Insights

- Fine Dining establishments consistently achieve higher ratings.
- Delivery restaurants dominate in volume.
- Customer satisfaction varies significantly across restaurant categories.


## 📈 Key Findings

| Area | Finding |
|--------|----------|
| Restaurant Hotspots | BTM, Koramangala, and HSR Layout dominate the market |
| Online Ordering | Significantly improves customer engagement |
| Pricing Strategy | Higher prices do not guarantee better ratings |
| Cuisine Trends | North Indian cuisine leads in popularity |
| Customer Satisfaction | Fine Dining restaurants achieve the highest ratings |


## 💡 Business Recommendations

Based on the analysis:

- Restaurant owners should consider opening outlets in high-demand locations such as BTM and Koramangala.
- Businesses should leverage online ordering platforms to increase customer reach.
- Focus on food quality and service rather than premium pricing alone.
- Emerging cuisine segments provide opportunities for market differentiation.


## 📷 Sample Visualizations

The notebook contains visualizations including:

- Restaurant Distribution by Location
- Online Ordering vs Customer Engagement
- Cost vs Rating Analysis
- Cuisine Popularity Distribution
- Restaurant Category Comparison

### 📍 Restaurant Distribution by Location
![Restaurant Distribution](https://github.com/user-attachments/assets/548dc9a4-1187-4d7a-9e1d-41233a947379)


### 🍜 Cuisine Popularity Analysis
![Cuisine Analysis](https://github.com/user-attachments/assets/e75edcf9-6e88-4b1c-b8c8-ef8850bb9a43)


### 🛒 Online Ordering Analysis

![Online Ordering Analysis](https://github.com/user-attachments/assets/ade5217a-d965-417b-bbe0-a9f64dee9fe0)


## 🚀 Skills Demonstrated

### Data Analysis

- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Statistical Interpretation
- Insight Generation

### Visualization

- Univariate Analysis
- Bivariate Analysis
- Data Storytelling
- Business Reporting

### Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook


## 📁 Project Structure

```
zomato-restaurant-analysis/
│
├── zomato_eda.ipynb
├── zomato.csv
├── images/
│   ├── location_analysis.png
│   ├── online_order_analysis.png
│   ├── cuisine_analysis.png
│   └── cost_rating_analysis.png
│
└── README.md
```


## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

- Working with real-world datasets
- Data cleaning and preprocessing techniques
- Exploratory data analysis workflows
- Business-oriented data interpretation
- Visual storytelling using Python
