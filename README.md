# Ecommerce-online-store-Analystlab-internship-project

## 📌 Project Overview
This project presents a comprehensive, interactive **Online Retail Analysis Dashboard** designed to evaluate business performance, customer buying patterns, and product trends for an e-commerce retail business. The dashboard translates raw transactional data into actionable insights regarding revenue generation, regional performance, and inventory demand.

## 📊 Key Insights & Business Value
* **Revenue Performance:** The business achieved a strong performance with a **Total Revenue of $8.28M** across **5M products sold**, serving over **401K unique customers**.
* **Geographical Dominance:** The **United Kingdom** stands out as the primary market, generating the lion's share of revenue ($6.7M) compared to other countries like Switzerland and Sweden.
* **Seasonality & Peaks:** Sales show a steady upward trajectory starting from Q3, reaching an absolute peak in **November ($1.13M)**, likely driven by holiday shopping behavior.
* **Product Demand:** *"ZINC T-LIGHT HOLDER"* emerged as the top-performing product, securing **4.9K in quantity sold**.

---

## 🛠️ Data Architecture & Cleaning Workflow
Before designing the visuals, a rigorous data cleaning process was executed to ensure data integrity:
1. **Handling Missing Values:** Addressed null values within critical fields (e.g., CustomerID, Description) to avoid skewed metrics. Unidentified regions were categorized as "Unspecified".
2. **Data Transformation:** * Extracted `Month` and `Year` from the raw `InvoiceDate` to build the chronological trend analysis.
   * Standardized product descriptions to title casing for clean visualization labels.
3. **Outlier & Consistency Checks:** Filtered out negative quantities and prices representing returns or cancellations to reflect true gross revenue performance.

---

## 🧩 Dashboard Features & Components
* **KPI Cards:** High-level metrics tracking Total Revenue ($8.28M), Total Quantity (5M), and Total Customers (401K).
* **Time-Series Analysis:** A line chart mapping *Revenue by Month* to spot seasonal sales trends.
* **Product Analytics:** Dual horizontal bar charts identifying the *Top Selling Products* and *Most Purchased Products*.
* **Customer Segmentation:** A donut chart tracking *Customer Purchasing Behavior* categorized by high, medium, and low-spending tiers.
* **Interactive Slicers:** Dynamic filtering capabilities using `InvoiceDate` and `Country` dropdowns for deep-dive regional analysis.

---

## 💻 Tech Stack
* **Business Intelligence Tool:** Power BI / Excel (Specify your tool here)
* **Data Transformation:** Power Query / DAX
