
#  Supply Chain Analytics Project

##  Project Overview
This project performs a **comprehensive Supply Chain Analysis** using Python and Power BI to identify inefficiencies, reduce stockouts, and optimize inventory decisions.

The analysis transforms raw operational data into **actionable insights** across:
- Inventory Management
- Demand Analysis
- Supplier Performance
- Warehouse Optimization
- Risk & Reorder Strategy

---

## Business Objectives
- Identify supplier delays and inefficiencies
- Analyze demand patterns
- Reduce stockouts and overstock
- Improve reorder decisions
- Optimize supply chain performance

---

## Tools & Technologies
- Python (Pandas, NumPy)
- Matplotlib & Seaborn
- Power BI
- Jupyter Notebook

---

##Dataset Overview

### Columns & Data Types

| Column Name                     | Data Type   | Description |
|--------------------------------|------------|-------------|
| SKU_ID                         | String     | Unique product identifier |
| Category                       | String     | Product category |
| Warehouse_ID                   | String     | Warehouse location |
| Supplier_ID                    | String     | Supplier reference |
| Quantity_On_Hand               | Integer    | Available stock units |
| Avg_Daily_Sales                | Float      | Average daily sales |
| Lead_Time_Days                 | Integer    | Delivery lead time |
| Reorder_Point                  | Integer    | Reorder threshold |
| Safety_Stock                   | Integer    | Buffer stock |
| Total_Inventory_Value_USD      | Float      | Inventory value |
| Supplier_OnTime_Pct            | Float      | On-time delivery % |
| Forecast_Next_30d              | Integer    | Demand forecast |
| Damaged_Qty                    | Integer    | Damaged units |
| Returns_Qty                    | Integer    | Returned units |
| Expiry_Date                    | Date       | Product expiry |

---

##  Methodology

1. Data Collection  
2. Data Understanding  
3. Data Cleaning  
4. Feature Engineering  
5. Exploratory Data Analysis  
6. Inventory Analysis  
7. Demand Analysis  
8. Supplier Analysis  
9. Warehouse Analysis  
10. Risk Analysis  
11. Reorder Optimization  
12. Visualization  

---

## Feature Engineering

- **Available_Stock**
- **Stock_Status**
- **Days_of_Inventory**
- **Coverage_Gap**
- **Demand_Supply_Ratio**
- **Supplier_Risk**
- **SC_Risk_Score**
- **Optimization_Score**

---

## Key Insights

###  Inventory
- Stock imbalance (overstock + stockouts)
- Many SKUs in low stock
- Coverage gap exists

 Inventory is not balanced

---

###  Demand
- Right-skewed distribution
- Few products drive demand
- High-demand SKUs risk stockouts

 Use ABC classification

---

###  Supplier
- Majority Class A suppliers
- Some delays impacting supply

Small delays → big impact

---

###  Warehouse
- Uneven stock distribution
- Overstock + shortages

Need redistribution strategy

---

###  Risk
- High stockout risk in fast-moving items
- Supplier delays worsen risk

 Risk = High demand + Low stock + Long lead time

---

### Reorder
- Many SKUs need reorder
- Delays increase stockouts

Automate reorder system

---

## Critical Insight
> ⚠ Demand exceeds stock in key categories  
> Immediate replenishment required

---

##  Recommendations

### Inventory
- Implement safety stock
- Improve forecasting

### Supplier
- Monitor risk suppliers
- Use SLA agreements

### Warehouse
- Redistribute inventory
- Real-time tracking


### Reorder
- Many SKUs need reorder
- Delays increase stockouts

 Automate reorder system

---

### Reorder

Reorder if Stock < Demand during Lead Time


### Risk
- Focus on high-risk SKUs
- Maintain buffer stock

---

## Key Outcomes
- Reduced stockout risks
- Improved supplier evaluation
- Better demand-supply alignment
- Data-driven decisions

---

## Project Files
- `final_project.pbix` → https://drive.google.com/file/d/1tfIvwORavEIzcEOhLg32y6ZBWstwdP_y/view?usp=sharing 
- `analysis.ipynb` → [Python Analysis](https://colab.research.google.com/drive/1b77qzyPeJE10F87oVwJoK57q2DQwp2YL?usp=sharing)  


---

##  Conclusion
This project demonstrates how analytics can:
- Improve inventory efficiency
- Reduce risks
- Optimize supply chain decisions

---

## ⭐ Author
**Ragavi R**

---

## ⭐ Support
If you like this project, give it a ⭐ on GitHub!
