
# Hospitality Revenue Analytics Dashboard (Power BI)

An end-to-end **Business Intelligence Dashboard** built using **Power BI** to analyze hotel performance across multiple cities, properties, room categories, and booking platforms.

This project focuses on revenue optimization, occupancy analysis, cancellation behavior, and customer satisfaction tracking to support data-driven decision-making in the hospitality industry.

---

## Project Overview

The Hospitality Revenue Analytics Dashboard transforms structured hotel booking data into interactive visual insights.

It enables stakeholders to:

* Monitor revenue and booking KPIs
* Track occupancy and capacity utilization
* Analyze cancellation trends
* Compare city and property performance
* Evaluate room category efficiency
* Measure customer satisfaction through ratings
* Identify high-performing booking platforms

This dashboard acts as a centralized performance monitoring solution for hotel management.

---

## Data Model & Architecture

The dataset is modeled using a **Star Schema** in Power BI for optimized performance and scalability.

### Fact Table

**fact_bookings**

* Booking ID
* Booking Status (Checked-out, Cancelled, No Show)
* Revenue
* Booking Platform
* Room Category
* Check-in / Check-out Dates
* Ratings
* Capacity & Occupancy Metrics

### Dimension Tables

* **dim_hotels** – Property and City details
* **dim_date** – Calendar hierarchy (Year, Month, Week)
* **dim_rooms** – Room Categories (RT1, RT2, RT3, RT4)

---

## Dashboard Structure

The Power BI report consists of **5 Analytical Pages**:

---

## 1️. Overall Hospitality Analysis

### KPIs

* Total Revenue (1.7bn)
* Occupancy % (58%)
* Average Rating (3.62)
* Cancellation Rate (24.8%)
* LDC (Lead Days Count)

### Visualizations

* Revenue by City
* Occupancy % by City
* Average Rating by City
* Weekly Trend (Revenue & Rating)
* Booking Platform Contribution
* Weekend vs Weekday Occupancy Ratio
* Property-Level Performance Table

**Purpose:**
Provides a high-level executive summary of overall business performance.

---

## 2. Monthly Analysis

### KPIs

* Monthly Revenue
* Occupancy %
* Average Rating
* Cancellation Rate
* LDC

### Visualizations

* Capacity vs Bookings vs Cancelled Bookings (Room Category Comparison)
* Revenue Calendar View (Day-wise Analysis)
* Property-wise Monthly Performance Table
* Platform-wise Bookings vs Cancelled Bookings
* Month Filters (May, June, July)

**Purpose:**
Analyzes operational efficiency and monthly booking patterns.


---

## 3. Property Performance Analysis

### KPIs

* Total Bookings (135K)
* Occupancy % (58%)
* Cancellation Rate (24.8%)
* Total Capacity (233K)
* Average Rating (3.62)

### Visualizations

* Total Bookings by Property
* Revenue Realized by City
* Occupancy % by Room Category (Donut Chart)
* Detailed Property Performance Table
* Rating vs Revenue Analysis

**Purpose:**
Compares individual property efficiency, utilization, and revenue contribution.

---

## 4. Cancellation Analysis

### KPIs

* Total Bookings (135K)
* Revenue Generated (2bn)
* Total Cancelled Bookings (33K)
* Cancellation Rate (24.8%)

### Visualizations

* Cancelled Bookings by City
* Cancelled Bookings by Room Category (Treemap)
* Cancelled Bookings by Year
* Booking Status Distribution (Donut Chart)
* Occupancy % vs Cancellation Rate
* Cancelled Bookings by Weekday (Waterfall Chart)
* Property-wise Cancellation Table

**Purpose:**
Identifies cancellation patterns to reduce revenue leakage and improve forecasting accuracy.

---

## 5. Customer & Rating Analysis

### KPIs

* Average Rating (3.62)
* Occupancy %
* Ratings Given (205K)
* Revenue Realized (2bn)

### Visualizations

* Average Rating by Year
* Average Rating by Room Category
* Average Rating by City
* Rating vs Revenue Scatter Plot
* Booking Gauge (Total Bookings)
* City-wise Rating, Revenue & Cancellation Matrix

**Purpose:**
Evaluates customer satisfaction and its impact on revenue performance.

---

## Key DAX Measures

The following calculated measures drive all KPIs and visualizations:

* Total Revenue
* Total Bookings
* Total Capacity
* Occupancy %
* Average Rating
* Cancellation Rate %
* Revenue Realized
* LDC (Lead Days Count)
* Weekend vs Weekday Occupancy Ratio

---

## Tools & Technologies

* **Power BI Desktop** – Data Modeling & Visualization
* **DAX** – Business Calculations
* **Power Query** – Data Cleaning & Transformation
* **Excel / CSV** – Source Data

---

## Repository Structure

```
Hospitality-Revenue-Analytics/
│
├── Hospitality_Analytics.pbix
├── data/
├── screenshots/
├── model_view/
└── README.md
```

---

## How to Run the Project

1. Clone this repository.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Update data source paths if required.
4. Refresh the dataset.
5. Use slicers (City, Property, Platform, Month, Week) to interact with dashboards.

---

## Business Impact

This dashboard helps hotel management to:

* Reduce revenue loss from cancellations
* Improve occupancy planning
* Optimize booking platform strategies
* Identify high-performing properties
* Enhance customer satisfaction
* Drive overall revenue growth

---

