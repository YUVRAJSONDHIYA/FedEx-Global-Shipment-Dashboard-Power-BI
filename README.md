# FedEx Global Shipment Analysis Dashboard using Power BI

## 📄 Project Overview

This Power BI project provides a comprehensive analysis of the SCMS (Supply Chain Management System) delivery history dataset, visualized as a modern, professional dashboard for FedEx. The primary goal is to deliver actionable insights into global shipment volumes, costs, delivery performance, and logistical distributions across various countries, shipment modes, and fulfillment channels.

---

## 🚀 Dashboard Features

### Key Performance Indicators (KPIs)
A top-level summary of the most critical metrics:
- **Total Shipments:** Overall count of shipments.
- **Total Value (USD):** Total monetary value of all shipments.
- **On-Time Deliveries %:** The percentage of shipments delivered on or before the scheduled date.
- **Avg Delay (Days):** The average delay in days for late shipments.
- **Freight Cost (USD):** Total cost incurred for freight.

### Interactive Visualizations
- **Global Shipments by Country:** A world map where bubble size represents the total shipment value for each country.
- **Top 10 Countries by Shipment Value:** A bar chart highlighting the most valuable markets.
- **Shipment Mode Distribution:** A donut chart showing the breakdown of shipments by mode (e.g., Air, Truck, Ocean).
- **Fulfillment Source Breakdown:** A donut chart illustrating the distribution of order fulfillment sources.

### Key Functionalities
- **Dynamic Filtering:** Slicers for **Year** and **Country** allow for deep-dive analysis into the data.
- **Cross-Filtering:** All visuals are interactive. Clicking on a data point in one visual filters all other visuals on the page.
- **Custom Theme:** A custom dark theme with FedEx's official corporate branding (purple and orange) for a polished and professional look.

---

## 🛠️ Technical Details

- **Tool Used:** Microsoft Power BI
- **Dataset:** SCMS Delivery History Dataset (`.csv`)
- **DAX (Data Analysis Expressions):** Used for creating calculated columns and measures, such as the `On-Time Delivery %`.

### Data Preparation & Transformation

Before visualization, the following data preparation steps were performed in Power Query and Power BI:
1.  **Data Cleaning:** Checked for and handled missing or inconsistent values.
2.  **Data Type Correction:** Ensured that date, numerical, and text columns were correctly formatted.
3.  **Calculated Columns:** Created new columns using DAX to determine delivery status ('On-Time' vs. 'Delayed').
4.  **Data Formatting:** Standardized currency fields to USD ($) for consistency across all visuals.

---

## 🔗 How to Use

1.  Clone this repository or download the `.pbix` file.
2.  Download the dataset file: `SCMS_Delivery_History_Dataset.csv`.
3.  Open the `.pbix` file in Power BI Desktop.
4.  If prompted, update the data source connection to the location of the downloaded CSV file on your local machine.

---

## ✒️ Author

- **Yuvraj Sondhiya**
- **LinkedIn:**  (https://www.linkedin.com/in/yuvrajson/)
