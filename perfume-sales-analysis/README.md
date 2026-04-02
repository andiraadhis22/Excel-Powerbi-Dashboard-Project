# eBay Perfume Sales 2024 Dashboard

## Project Overview
This project analyzes eBay fragrance listings to evaluate product performance and demand patterns, with the goal of helping resellers make more informed product selection decisions and reduce dead stock risk.

The analysis follows a structured workflow including **data cleaning, data processing, and data visualization**. Data preparation was performed using Power Query in Excel, and the dashboard was built in Power BI.

Source: https://www.kaggle.com/datasets/kanchana1990/perfume-e-commerce-dataset-2024

## Report Preview

Below is a preview of the dashboard:

![Report Preview](images/preview.png)

## Steps Involved

### 1. Data Cleaning
Before analysis, the dataset was cleaned to ensure consistency and accuracy:
- Removed duplicate records across multiple source files
- Standardized text fields such as Brand, Title, Type, and Item Location
- Trimmed and cleaned text to remove formatting issues and hidden characters
- Handled inconsistent and invalid values in perfume type and brand naming

### 2. Data Processing
To prepare the dataset for analysis, several transformations were applied:
- Reclassified perfume types into standardized categories (Eau de Parfum, Eau de Toilette, Eau de Cologne, etc.)
- Extracted currency from the pricing field and structured the price format
- Converted data types (text to numeric and datetime)
- Created a **Price_USD** column for consistent price comparison
- Derived **Gender segmentation** (Men/Women) based on dataset source
- Structured item location into **City, State, and Country**
- Standardized brand naming (e.g., CK → Calvin Klein, YSL → Yves Saint Laurent)

### 3. Data Visualization
An interactive dashboard was developed in Power BI to analyze:
- Sales distribution by perfume type
- Revenue and volume by gender segment
- Brand performance comparison
- Pricing patterns and sales behavior
- Seller distribution by geographic location

## Key Insights from the Report

### 1. Product Performance
- Eau de Toilette (EDT) shows the highest sales volume, especially in the Men’s segment
- Eau de Parfum (EDP) generates higher value per item due to higher pricing

### 2. Customer Segment
- The Men’s segment generates the highest revenue and total units sold
- The Women’s segment shows stronger preference for higher-priced EDP products

### 3. Pricing & Sales Behavior
- Most transactions occur within the mid-price range ($45–$75), where demand is strongest
- Stock availability does not reliably predict sales performance
- Brand positioning and pricing have a greater impact on sales than stock quantity

### 4. Brand Performance
- A small number of established brands dominate sales across multiple segments
- Some brands offer a wide product range but generate lower sales per item

### 5. Seller Distribution
- The United States has the highest concentration of active sellers and sales volume
- Sellers in Hong Kong tend to offer higher-priced, premium fragrance products
- Sellers in China focus on lower-priced products with relatively lower sales volume
- Other regions show minimal seller activity and do not form a clear pattern
- Item location represents seller location, not customer demand, as products can be shipped globally

## Conclusion
This analysis suggests that dead stock risk in the fragrance resale market is closely related to how well product selection aligns with actual demand patterns. A small number of products generate most of the sales, while many others sell at much lower levels, indicating that demand is highly concentrated rather than evenly distributed. Stock availability alone does not guarantee stronger sales performance, and selecting products without considering these demand patterns increases the risk of slow-moving inventory. Therefore, a more demand-driven approach to product selection can help improve inventory turnover and reduce potential dead stock risk.

## Recommendations
- Focus on high-demand product types such as EDT for volume and EDP for higher value
- Prioritize established brands with consistent performance across segments
- Optimize pricing within the high-demand mid-range segment ($45–$75)
- Avoid relying solely on stock levels as a performance indicator

## Contact
LinkedIn: https://www.linkedin.com/in/adhisandira  
Email: andiraadhis@gmail.com
