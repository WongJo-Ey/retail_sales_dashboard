# 🧩 Power BI Sales Dashboard

An interactive Power BI dashboard designed to explore product sales, revenue distribution, and customer contribution using a real-world retail dataset.

---

## 📊 Key Features

- **Total Revenue & Product KPIs** – Highlights overall performance with clear, easy-to-read cards.
- **Monthly Revenue Line Chart** – Visualizes sales trends and seasonality across the year.
- **Top 10 Customers by Revenue** – Displays the most valuable customers based on their total spend and quantity purchased.
- **Best-Selling Products Table** – Lists the top products by quantity sold with interactive filtering.
- **Global Sales Map** – Geographic visualization of where products are sold across different regions.
- **Interactivity** – Clicking on any product filters the entire report:
  - See which **regions** purchase the selected product the most.
  - Understand how much each **top customer** contributes to that specific product.

---

## 📂 Dataset

- **Source**: https://www.kaggle.com/code/sinaasappel/ecommerce-data-exploration-and-visualization
- **Fields used**:
  - `InvoiceDate`, `CustomerID`, `Country`, `Description`, `Quantity`, `UnitPrice`
- **Calculated Fields**:
  - `TotalPrice = Quantity * UnitPrice`
  - `Year-Month` columns for trend analysis
---

## 🛠️ Tools Used

- **Power BI Desktop**
- **Power Query** for data cleaning and transformation
- **DAX** for dynamic KPIs and custom calculations
- **Slicers & Bookmarks** for reset buttons and filters

---

## 🖼️ Dashboard Preview

![Screenshot 2025-06-15 235926](https://github.com/user-attachments/assets/825168cf-2ffc-466a-a023-0d46eaacdb53)

---

## 🚀 How to Use

1. Download the `.pbix` file from this repository.
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop).
3. Use the slicers or click product/customer rows to explore deeper insights.
4. Interact with the map and visuals for detailed region- or customer-specific breakdowns.

---
