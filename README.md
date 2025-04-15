# Inventory-Management-for-business-planning-using-python

Inventory is a necessary evil. 

Dataset used: [(https://www.kaggle.com/competitions/m5-forecasting-accuracy)]
## 📘 Overview
It refers to all the goods a business holds, including raw materials, work-in-progress, and finished products, for sale or use in production. Holding an inventory is expensive but not keepig is not an option in many cases. 

## 🎯 Why Inventory Management Matters
An organization’s inventory, is central to business operations and a primary source of revenue generation. Inventory can be classified in numerous ways, and how well it’s managed directly affects an organization’s order fulfillment capabilities.
For example, in keeping track of raw materials, safety stock, finished goods, or even packing materials, businesses are collecting crucial data that should inform future purchasing and fulfillment operations. Understanding purchasing trends and the rates at which items sell determines how often companies need to restock inventory and which items are prioritized for repurchase. Having this information on hand can improve customer relations, cash flow, and profitability while also decreasing the amount of money lost to wasted inventory, stockouts, and restocking delays.

Hence, inventory management is crucial in business processes.It is the business process that ensures a company has the right amount of the right items in the right place at the right time. It includes oversight of everything from ordering and storing inventory to using or ultimately selling it.

For many businesses, such as manufacturers and retailers, inventory is one of their most valuable assets, enabling them to meet customer demand and make money. But inventory can also be a drain on profitability if not carefully managed. Holding on to too much inventory carries significant costs, and there is also the risk of spoilage, theft, and damage to factor into the equation. The goal of effective inventory management is to achieve a just-right level to avoid overstocking, shortages, or stockouts, all of which can be extremely costly to a business.

Various inventory models:
![image](https://github.com/user-attachments/assets/1432e54a-152e-4b7d-91da-27275273125e)
Each model have different scenarios when they should be applied. In this project we observed sales of the stores and calculated reorder point , safety stock, high risk items accordingly. 

Related terms:
- **Reorder point** : The reorder point is the inventory level at which a new order should be placed to replenish stock before it runs out. It is calculated based on the lead time demand and may include safety stock to avoid stockouts.
Formula:

Reorder Point= Average Demand During * Lead Time + Safety Stock

- **Safety Stock** : It is the extra inventory kept on hand to mitigate the risk of stockouts caused by demand variability or delays in supply. It acts as a buffer against uncertainties in demand and lead time.
  
- **ABC Analysis** : ABC analysis is an inventory categorization technique that divides items into three categories (A, B, and C) based on their importance, typically measured by annual consumption value:

-     A-items: High-value, low-quantity items — tightly controlled.

-     B-items: Moderate-value, moderate-quantity items — less tightly controlled.

-     C-items: Low-value, high-quantity items — simplest controls.
- 
### Replenishment policies are based on metrices such as:
- CSL
- IFR Inventory fill rate 


### 🛠 Project Scope
In this project, we:
Observed sales data from stores

Calculated:

- Reorder Points
- Safety Stock
- Identified high-risk items
- Performed ABC Analysis to prioritize inventory focus

This is a granular analysis, done at the item level. It can be further expanded region-wise or store-wise to get deeper insights.

## 📦 Replenishment Policies
Replenishment policies help determine when and how much to reorder based on demand uncertainty, service levels, and business priorities.

### 🔢 Common Metrics Used:
- **Cycle Service Level (CSL)**:
CSL represents the probability that demand during the lead time will be fully met without a stockout.
For example, a CSL of 95% means there is a 95% chance that no stockout will occur during the lead time.

- **Inventory Fill Rate (IFR)**:
IFR refers to the percentage of total demand that is fulfilled from available inventory, including partial shipments.
It answers the question: What fraction of demand was actually met without delay?

## 📌 Application in This Project
In this project, we used a 95% Cycle Service Level (CSL) to calculate the reorder point, meaning we aim to meet demand during the lead time in 95 out of 100 cycles.

This level of service ensures high product availability while keeping inventory costs reasonable — striking a balance between customer satisfaction and holding costs.



Inspired by this excellent Medium article:
📖 [Inventory Management for Retail – Stochastic Demand](https://medium.com/data-science/inventory-management-for-retail-stochastic-demand-3020a43d1c14)

##  Future Enhancements
Expand analysis to include:
- Region-wise insights
- Store-level optimization 
- Integrate forecast models for dynamic reorder points.
  
 
