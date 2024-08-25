# ✈️ Airline Flight Delay Analysis with Power BI

## Project Overview

In this demo, we’ll assume the role of a Data Analyst for the Federal Aviation Administration 🛩️. We’ve been granted access to a comprehensive database containing nearly 2,000,000 commercial flights from major US airports. Our mission is to analyze this data to determine which flights were delayed or canceled, and uncover the reasons behind these disruptions.The key objectives included cleaning and preparing the data, building a relational model, creating insightful metrics with DAX, and developing a comprehensive dashboard to visualize key performance indicators (KPIs) related to flight delays, cancellations, and on-time performance.

Using **Power BI**, we’ll transform the raw data into a user-friendly, interactive dashboard that enables stakeholders to explore flight delays and cancellations by airport, airline, day of the week, and more.

## Key Features

- **Data Loading & Transformation**: Efficiently load and clean the raw data, preparing it for analysis.
- **Relational Data Modeling**: Build a robust relational data model to ensure accurate and insightful analysis.
- **Calculated Columns & DAX Measures**: Add calculated columns and DAX measures to enhance the dataset and provide deeper insights.
- **Interactive Dashboard Design**: Create a visually stunning and interactive dashboard that allows stakeholders to drill down into specific areas of interest.

## Workflow

1. **Load and Transform Data**:
   - Import data from multiple sources.
   - Cleanse and preprocess the data for analysis.
   - Ensure data quality and integrity.

2. **Build a Relational Data Model**:
   - Create relationships between tables.
   - Define primary and foreign keys.
   - Establish the foundation for accurate reporting.

3. **Add Calculated Columns & DAX Measures**:
   - Implement calculated columns for key metrics.
   - Develop DAX measures to perform complex calculations.
   - Optimize performance for large datasets.

4. **Design the Interactive Dashboard**:
   - Create a user-friendly interface with filters and slicers.
   - Use visuals like charts, graphs, and maps to present data.
   - Provide actionable insights with drill-through capabilities.
  

## Project Structure Detailed Workflow

### 1. Data Cleaning and Preparation
- **Data Preparation:** 
  - Explored and validated the dataset using Power Query Editor.
  - Ensured data quality and consistency.
- **Data Cleaning:** 
  - Performed preprocessing by creating new columns for better grouping and readability.
  - Added conditional columns for dynamic analysis.
  - Removed unnecessary columns to optimize the dataset.
- **Data Types and Headers:** 
  - Ensured correct data types for each column.
  - Promoted the first row as headers.
  - Loaded the cleaned data into Power BI for further analysis.

### 2. Building a Relational Model
- **Relational Model Setup:** 
  - Established relationships between tables using the primary key of the lookup table and the foreign key of the fact table.
  - Followed a one-to-many star schema to maintain data integrity.
- **Simplification:** 
  - Utilized Power BI’s relationship-building features to connect tables without complex SQL joins.

### 3. Adding DAX Measures
- **Objective:** 
  - Enhanced the data model by creating new fields and metrics to support detailed analysis.
- **Key Measures:**
  - `Total Flights`
  - `Cancelled Flights`
  - `Delayed Flights`
  - `On-Time Flights`
  - Percentage metrics for delayed, cancelled, and on-time flights.

### 4. Data Visualization and Dashboard Development
- **Wireframe Design:** 
  - Pre-designed a wireframe to outline the dashboard’s layout and key KPIs.
- **Dashboard Features:**
  - **Total Flights:**
    - Monthly trends.
    - Total flights by airport.
    - Breakdown by on-time, delayed, and cancelled flights.
  - **Delayed Flights:**
    - Monthly trends.
    - Delay rate by airline.
  - **Cancelled Flights:**
    - Analysis by type and by day of the week.
  - **Visualization Types:**
    - Used various charts including cards, line charts, clustered bar charts, donut charts, and stacked bar charts.
  - **Interactive Features:**
    - Implemented visual interactions for cross-filtering based on user selections.

### 5. Key Insights
- **Dallas Operations:**
  - 239,551 flights operated with 57.2% on time.
  - JetBlue identified as the least reliable airline.
- **Cancellation Patterns:**
  - Cancellations were most common on Mondays and Sundays.
  - Nearly 75% of cancellations were due to weather conditions.
- **Airline Performance:**
  - The dashboard allows users to select an airline to view its performance metrics, including total flights, on-time percentage, delay rate, and cancellation percentage.

## Conclusion
The Flight Delay Analysis project provides a detailed understanding of flight delay patterns, offering actionable insights for decision-making in airline selection and operational improvements. The Power BI dashboard serves as a powerful tool for visualizing and interpreting flight data.



