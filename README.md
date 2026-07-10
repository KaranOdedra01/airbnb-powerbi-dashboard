# Airbnb Market Performance & Customer Review Analytics Dashboard

## Project Overview

This project showcases an interactive Power BI dashboard developed to analyze Airbnb listing and customer review data. By integrating listing details with customer reviews, the dashboard provides meaningful insights into pricing strategies, customer engagement, host performance, room type distribution, and geographic trends.

The project demonstrates practical Business Intelligence techniques including data preparation, data modeling, DAX calculations, KPI development, and interactive dashboard design.

---

## Business Problem

Airbnb hosts and property managers need actionable insights to understand customer behavior, pricing patterns, and listing performance. Raw datasets alone make it difficult to identify trends and compare performance across neighborhoods and property types.

This dashboard transforms raw Airbnb data into interactive visualizations that support informed business decisions.

---

## Objectives

- Analyze Airbnb listing performance.
- Understand customer review behavior.
- Compare room types and pricing.
- Identify top-performing hosts.
- Explore geographic distribution of listings.
- Build an interactive dashboard for business analysis.

---

## Dataset Information

The project uses two datasets.

### Listings Dataset

Contains property information including:

- Listing ID
- Host Name
- Room Type
- Price
- Neighborhood
- Availability
- Latitude
- Longitude
- Review Scores

### Reviews Dataset

Contains customer review information including:

- Listing ID
- Review Date
- Reviewer Name
- Review Comments

---

## Data Preparation

The following preprocessing steps were performed before creating the dashboard.

- Removed unnecessary columns
- Verified data quality
- Standardized data types
- Cleaned missing values
- Created relationships between datasets
- Performed an **Inner Join** using:

```
Listings.id = Reviews.listing_id
```

- Built calculated measures using DAX
- Designed an optimized data model

---

## Dashboard Features

The dashboard includes the following visualizations:

- KPI Cards
- Interactive Map
- Bar Charts
- Donut Chart
- Scatter Plot
- Gauge Chart
- Monthly Trend Analysis
- Interactive Slicers
- Dynamic Filtering

---

## Key Performance Indicators (KPIs)

- Total Reviews
- Total Hosts
- Total Reviewers
- Average Rating

These KPIs provide a quick overview of marketplace performance.

---

## Dashboard Insights

The dashboard helps answer important business questions such as:

- Which room type receives the highest number of reviews?
- Which hosts have the highest customer engagement?
- How are listings distributed geographically?
- Is there a relationship between price and customer ratings?
- How do review trends change over time?
- What is the distribution of available room types?

---

## Dashboard Pages

### Executive Overview

Provides a summary of business performance using KPIs and high-level visualizations.

### Customer Review Analysis

Analyzes customer engagement across room types and over time.

### Host Performance

Highlights hosts with the highest review counts.

### Pricing Analysis

Explores the relationship between listing prices and customer ratings.

### Geographic Insights

Displays listing locations using an interactive map for regional analysis.

---

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Data Cleaning
- Business Intelligence
- Data Visualization

---

## Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- Relationship Management
- DAX Calculations
- KPI Design
- Dashboard Development
- Interactive Reporting
- Business Analytics
- Data Visualization

---

## Dashboard Highlights

- Interactive filtering experience
- Business-focused KPIs
- Professional dashboard layout
- Geographic visualization
- Customer review analysis
- Pricing insights
- Host performance tracking
- Responsive visual design

---

## Future Enhancements

- Sentiment analysis of customer reviews
- Revenue forecasting
- Seasonal trend analysis
- Advanced DAX measures
- Drill-through pages
- Mobile-optimized dashboard
- Predictive analytics using machine learning

---

## Learning Outcomes

Through this project, I strengthened my understanding of:

- Building interactive dashboards in Power BI
- Data modeling using multiple datasets
- Creating effective business KPIs
- Designing professional data visualizations
- Transforming raw data into meaningful business insights

---

## Author

**Karan Odedra**

Computer Science Engineering Student with an interest in Data Analytics, Business Intelligence, Power BI, Tableau, SQL, Excel, and creating interactive dashboards that solve real-world business problems.

If you found this project helpful or interesting, consider giving it a ⭐ on GitHub.
