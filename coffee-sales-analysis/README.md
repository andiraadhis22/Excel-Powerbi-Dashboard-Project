#Coffee Sales Analysis Dashboard

## Project Overview
This project demonstrates an end-to-end data analysis process using Microsoft Excel. The primary focus is transforming raw relational data tables into an interactive dashboard. This workflow encompasses data cleaning, table merging using lookup functions, data aggregation via Pivot Tables, and dynamic visualization.

## Report Preview
Below is a preview of the dashboard:

![Report Preview](dashboard_image/preview.png)

## Tools & Functions Used
- **Microsoft Excel**
- **Data Retrieval:** INDEX and MATCH
- **Logical Functions:** IF for blank/error handling
- **Data Aggregation:** Pivot Tables
- **Interactive Elements:** Pivot Charts, Slicers, Timeline

## Steps Involved

### 1. Data Preparation & Merging
The initial dataset consists of three separate tables: Orders (fact table), `Customers`, and Products (dimension tables). Data preparation was performed directly in Excel:
- Retrieved customer attributes (*Customer Name*, *Email*, *Country*) from the Customers table into the Orders table using a combination of INDEX and MATCH functions.
- Retrieved product specifications (*Coffee Type*, *Roast Type*, *Size*, *Unit Price*) from the Products table using a combination of INDEX and MATCH functions.
- Applied IF logic to clean formatting, such as inserting text placeholders for blank Email cells.
- Calculated the Sales column by multiplying Quantity by *Unit Price*.

### 2. Data Processing (Pivot Tables)
Once the main Orders table was populated, the data was summarized using several Pivot Tables distributed across calculation sheets:
- **KPI Summary:** Aggregated top-level business health metrics, including Total Revenue ($45,134), Units Sold (3,551), Total Orders (1,000), and Average Order Value ($45.13).
- **Total Sales Over Time:** Aggregated total revenue by Year and Month to analyze historical trends and seasonality.
- **Sales by Country:** Calculated total sales per operating country to compare market penetration.
- **Top 5 Customers:** Sorted and filtered the top 5 customers based on their highest accumulated purchase value.

### 3. Dashboard Creation & Visualization
The Pivot Tables were compiled into a single, cohesive Dashboard sheet:
- Built a **Line Chart** to track monthly sales trends.
- Built **Bar Charts** to display country contributions and top customer rankings.
- Integrated interactive elements including **Slicers** (*Roast Type*, *Size*, *Loyalty Card*) and a **Timeline** (*Order Date*).
- Linked the Slicers to all charts using **Report Connections**, ensuring the entire dashboard responds to filters simultaneously.

## Key Insights
- **Geographical Concentration:** The United States market heavily dominates total revenue generation (approx. 79% or $35,638), significantly outpacing the Ireland and United Kingdom markets.
- **Product Performance & Preferences:** - Larger packaging sizes (2.5 kg) account for over 50% of the total revenue ($23,785). 
  - Among all variations, Excelsa beans paired with a Light Roast generate the highest sales volume.
- **Loyalty Program Anomaly:** Non-Loyalty customers demonstrate a higher Average Order Value ($46.48) compared to customers enrolled in the Loyalty program ($43.67), indicating a potential inefficiency in the current reward structure.
- **Time-Series Trends:** Sales exhibit significant monthly fluctuations, with peak performance recorded in February 2020 ($1,798.34).
- **Customer Lifetime Value:** A select group of top-tier customers consistently drive higher value, with the top 5 customers spending between $278 and $317 individually over the recorded period.

## Contact
LinkedIn: https://www.linkedin.com/in/adhisandira  
Email: andiraadhis@gmail.com
