🛍️ 2024 Myntra Sales Analysis – Power BI Dashboard

This Power BI project presents an in-depth analysis of Myntra's sales and product performance data. The dashboard reveals key business metrics such as revenue, discounting impact, top-selling categories, and customer preferences using interactive visuals.

---

📁Files Included

| File Name               | Description                                           |
|------------------------|-------------------------------------------------------|
| `power bi project.pbix` | Power BI dashboard with interactive visualizations.   |
| `Myntra dataset.xlsx`   | Cleaned dataset containing sales, category, and pricing info. |

---

📊 Dashboard Highlights

**Visuals Included:**

| Visualization                             | Description                                                                 |
|------------------------------------------|-----------------------------------------------------------------------------|
| 🔹 **Column Chart – Sales by Category**         | Identifies top-performing product categories and subcategories.             |
| 🔹 **Line Chart – Monthly Sales Trend**         | Shows sales fluctuation and growth over months.                             |
| 🔹 **Bar Chart – Gender vs Sales**              | Compares male vs female customer purchasing behavior.                       |
| 🔹 **Scatter Plot – Discount vs Units Sold**    | Reveals relationship between discounts and volume sold.                     |
| 🔹 **Tree Map – Brand Sales Contribution**      | Shows top brands by total revenue and their sales share.                    |
| 🔹 **Pie Chart – Rating Distribution**          | Distribution of product ratings (1 to 5 stars).                             |
| 🔹 **Map – Region-wise Sales**                  | Displays geographic sales contribution by state or city.                    |
| 🔹 **KPI Cards – Key Metrics**                  | Shows Total Sales, Avg. Order Value, Units Sold, Avg. Discount %.           |

---

📈 Insights Derived

- Categories like Footwear and Apparel dominate total revenue.
- Higher discounts correlate with greater units sold but not always higher revenue.
- Female shoppers generate slightly more sales, especially in certain categories.
- Products with higher ratings tend to perform better in terms of volume.
- Major sales are concentrated in metro cities like Delhi, Bangalore, and Mumbai.
- Some brands show high revenue but low ratings, indicating quality issues.

---

📌 Dataset Info

**Source:** Myntra (Simulated/Provided Dataset – 2024 Sample)  
**Columns Include:**
- `Order ID`
- `Product ID`
- `Category`, `Subcategory`
- `Brand`
- `Gender`
- `Selling Price`, `MRP`, `Discount %`
- `Rating`
- `City`, `State`
- `Order Date`

🧠 Technologies Used

- **Power BI Desktop** – Data modeling, dashboard design
- **Power Query** – Data cleaning and transformation
- **DAX Measures** – For KPIs such as:
  - `Total Sales`
  - `Average Discount %`
  - `Units Sold`
  - `Avg. Order Value (AOV)`
  - `Rating Count`
  - `Sales by Region/Brand/Category`


🧾 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/myntra-sales-powerbi.git
