
# Hotel Revenue Analytics Dashboard (Power BI)

Power BI dashboard analyzing hotel performance across multiple cities and properties.
The report focuses on **revenue, occupancy, bookings, and room category performance** to support data-driven decision-making in the hospitality domain.

---

## Project Overview

This project delivers an interactive **Hotel Revenue Analytics Dashboard** using **Power BI** that helps stakeholders:

* Track key revenue and occupancy KPIs
* Compare performance across cities and properties
* Analyze booking trends and customer behavior
* Evaluate room category performance
* Identify high-performing booking platforms

The dashboard transforms raw hotel booking data into **actionable business insights**.

---

## Dataset

The project uses structured hotel booking data stored in **Excel/CSV** format and modeled using a star schema.

### Fact Tables

* `fact_bookings` – booking-level details (dates, revenue, booking status, platform, room category, etc.)

### Dimension Tables

* `dim_hotels` – hotel and city information
* `dim_date` – calendar table for time-based analysis

---

## Power BI Report Structure

The report consists of **4 main pages**:

### 1.Hotel Revenue Dashboard (Executive Summary)

* KPI cards: **Total Revenue, Occupancy %, ADR, RevPAR**
* Total Revenue trend by **Year, Quarter, Month, and Day**
* Total Revenue by City
* City and Date slicers for interactive filtering

---

### 2.Revenue Analysis

* Total Revenue by Property
* Total Revenue by City
* Total Revenue by Booking Platform

---

### 3.Booking Trends

* Total Bookings by Day Type (Weekday vs Weekend)
* Total Bookings by Booking Status (Checked Out, Cancelled, No Show)
* Total Bookings by Year

---

### 4.City Performance & Room Analysis

* City-wise performance table:

  * Total Revenue
  * ADR
  * RevPAR
  * Occupancy %
* Occupancy % by City

* Room category analysis:

  * ADR
  * Total Revenue
  * Total Bookings
* ADR comparison between **Business** and **Luxury** categories

---

## Key Metrics / DAX Measures

Key business measures created using **DAX**:

* **Total Revenue**
* **Total Bookings**
* **Occupancy %**
* **ADR (Average Daily Rate)**
* **RevPAR (Revenue per Available Room)**
* **Cancellation Rate %**

These measures drive all KPIs and visuals in the dashboard.

---

## Tech Stack

* **Power BI Desktop** – data modeling & visualization
* **DAX** – calculated measures and KPIs
* **Power Query** – data cleaning and transformation
* **Excel / CSV** – source datasets

---

## Repository Contents

* `Hotel_Revenue_Analytics.pbix` – Power BI report file
* `data/` – source datasets
* `screenshots/` – dashboard screenshots
* `Queries/` – Power Query transformations / DAX documentation
* `model_view/` – Power BI data model screenshot
* `README.md` – project documentation

---

## How to Use

1. Clone or download this repository.
2. Open `Hotel_Revenue_Analytics.pbix` in **Power BI Desktop**.
3. Update data source paths if required.
4. Refresh the report and explore dashboards using slicers.

---