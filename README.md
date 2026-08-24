# 🏡 Airbnb Market Analysis Dashboard

## 📌 Project Overview

This project analyzes Airbnb data across **10 major cities**, covering over **250,000 listings** and more than **5 million historical reviews**.

The objective of this project is to understand how the Airbnb market differs across cities and identify patterns related to **listings, pricing, property types, ratings, host characteristics, and customer review behavior**.

The analysis was performed using **Power BI**, where the data was transformed into an interactive dashboard using **DAX measures, calculated columns, visualizations, filters, and bookmarks**.

---

## 🎯 Business Questions

This analysis focuses on answering the following questions:

1. How does the Airbnb market differ across cities?
2. Which cities have the highest number of listings?
3. How do property and room types differ across markets?
4. How does pricing vary across different accommodation types?
5. Which cities perform better based on guest ratings?
6. Are there any trends or seasonality in customer review activity?
7. How frequently do customers leave reviews?
8. How do host profile and identity verification characteristics vary?
9. Which cities may offer better value for travelers based on price and ratings?

---

## 📊 Dashboard Pages

### 1️⃣ Overview

The Overview page provides a high-level summary of the Airbnb market.

#### Key Metrics

- Total Listings
- Total Cities
- Total Hosts
- Property Types
- Total Reviews

#### Analysis Includes

- Distribution of listings across cities
- Comparison of Airbnb markets
- Accommodation and room type distribution
- Average price across room types
- Overall market concentration

---

### 2️⃣ Ratings Analysis

The Ratings page focuses on understanding the guest experience across different cities.

The analysis compares ratings such as:

- Accuracy
- Cleanliness
- Communication
- Location
- Value

This helps identify which cities perform better across different aspects of the customer experience.

---

### 3️⃣ Reviews Analysis

The Reviews page focuses on customer review behavior.

The analysis includes:

- Review frequency
- Number of distinct reviewers
- Cumulative review percentage
- Monthly review trends
- Review activity across cities
- Potential seasonality patterns

---

## 🧮 Key Concepts Used

### Data Modeling

Relationships were created between the Listings and Reviews tables to connect property information with customer review activity.

### DAX Measures

DAX was used to create calculations and KPIs such as:

- Total Listings
- Total Hosts
- Total Reviews
- Average Ratings
- Review Frequency
- Cumulative Reviewers
- Cumulative Review Percentage
- City Ranking

### Data Visualization

Different visualizations were used based on the type of business question being answered:

- **Cards** for high-level KPIs
- **Bar and Column Charts** for category comparisons
- **Line Charts** for trends over time
- **Combo Charts** for comparing values with cumulative percentages
- **Matrix Visuals** for comparing multiple rating metrics
- **Slicers and Filters** for interactive analysis

### Interactive Features

The dashboard also includes:

- Filters
- Slicers
- Bookmarks
- Buttons
- Navigation between different views

---

## 📈 Key Analytical Areas

### 🏙️ Market Comparison

Understanding how the size and structure of the Airbnb market differ across cities.

### 💰 Pricing Analysis

Comparing average prices across different room and accommodation types.

### ⭐ Customer Experience

Analyzing ratings to understand differences in guest satisfaction across cities.

### 📅 Review Behaviour

Exploring how frequently customers leave reviews and whether review activity changes over time.

---

## 🛠️ Tools Used

- Power BI
- Power Query
- DAX
- Data Modeling
- Data Visualization

---

## 📁 Repository Structure

```text
airbnb-data-analytics-project/
│
├── README.md
│
├── powerbi/
│   └── Airbnb_Market_Analysis.pbix
│
├── images/
│   ├── overview_dashboard.png
│   ├── ratings_dashboard.png
│   └── reviews_dashboard.png
│
└── docs/
    └── business_questions_and_insights.md
