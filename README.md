
🚜# Crop Market Price Tracking Database design

### **🚀Project Overview**

The **Crop Market Price Tracking System** is designed to **monitor, analyze, and predict** crop prices across multiple markets. By providing **real-time updates, trend analysis, and market insights**, it enables **farmers, traders, and policymakers** to make data-driven decisions, ensuring **market transparency and efficiency**.

### **Objectives**

- **Track and store** daily crop prices across diverse markets.
- **Analyze price trends** and fluctuations to identify market patterns.
- **Provide insights** into supply-demand dynamics for better planning.
- **Support stakeholders** (farmers, traders, policymakers) with data-driven decision-making.
- **Enhance supply chain efficiency** by forecasting demand-supply gaps.
- **Prevent price manipulation** and ensure fair trade practices.
- **Assist in policy formulation** by supplying accurate market data.

By **optimizing agricultural trade and reducing market volatility**, this system **empowers stakeholders**, promotes **sustainable farming**, and enhances **economic stability** in the agricultural sector. 🚜📊

### **🚜Entity-Relationship (ER) Diagram**

The **ER diagram** visually represents the relationships between key entities in the system. Below are the core entities and their relationships:

### **Key Entities:**

1. **Farmers** (Farmer_ID, Name, Phone, Location)
2. **Crops** (Crop_ID, Crop_Name, Season, Yield_Quantity)
3. **Farmers_Crops** (Farmer_Crop_ID, Farmer_ID, Crop_ID, Quantity)
4. **Market** (Market_ID, Market_Name, Location)
5. **Market_Transaction** (Transaction_ID, Market_ID, Farmer_Crop_ID, Transaction_Date)
6. **Market_Price** (Price_ID, Market_Transaction_ID, Price_per_kg, Transaction_Date)
7. **Supply_Demand** (Record_ID, Market_Transaction_ID, Supply_Quantity, Demand_Quantity, Record_Date)

![Untitled Diagram.drawio (3).png](https://github.com/RK1061/Crop-Market-Price-Tracking-Database-/blob/main/ER%20DIG/Untitled%20Diagram.drawio%20(4).png)

