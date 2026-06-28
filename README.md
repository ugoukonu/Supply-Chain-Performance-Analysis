# Supply-Chain-Performance-Analysis
Analysis of supply chain performance including delivery delays, supplier evaluation, product defects, cost trends, and order behaviour segmentation using Python.
# Supply Chain Performance Analysis

## Overview
This project analyzes supply chain performance across multiple suppliers, product categories, and warehouse destinations. It explores delivery delays, defect rates, cost trends, and order behaviour to uncover operational inefficienciesand provide actionable recommendations.

## Objectives
- Perform data transformation and feature engineering on raw supply chain data
- Analyze delivery performance across suppliers and product categories
- Identify root causes of late deliveries
- Segment orders by size, cost, and delivery speed
- Visualize trends and patterns using Python

## Tools Used
- Python — data transformation, feature engineering, and EDA
- Pandas — data manipulation and cleaning
- Matplotlib — data visualization
- Seaborn — statistical visualization

## Dataset
The dataset contains supply chain order records including:
- Order details (order ID, date, product category, quantity, unit price)
- Supplier information (name, location)
- Delivery details (lead time, actual delivery days, delivery status)
- Product quality (defects, return status)
- Warehouse destination

## Key Findings
- Supplier E has the highest number of delayed deliveries (155 delays)
- Connectors are the most delayed product category (93 delays)
- Medium-sized orders with fast delivery speed incur the highest average costs
- Systematic delivery delays are concentrated in early 2022

## Notebook Structure
- **Section 1:** Data Transformation & Feature Engineering
- **Section 2:** Matplotlib Fundamentals & Visualization
- **Section 3:** Exploratory Data Analysis (EDA)


## Recommendations

### Supplier Management
- Review and renegotiate contracts with Supplier E who accounts for the highest 
  number of delayed deliveries; consider reducing order volume or setting stricter 
  delivery terms
- Diversify supplier base to reduce over-reliance on a single supplier and minimise 
  supply chain disruption risk

### Delivery Performance
- Introduce penalty clauses for suppliers who consistently exceed agreed lead times
- Increase lead time buffers for high-delay product categories such as Connectors 
  and Fasteners
- Closely monitor order fulfilment during early-year periods where delays are most 
  concentrated

### Product Quality
- Implement pre-acceptance quality checks to reduce defect rates before goods enter 
  the warehouse
- Establish a structured return tracking system to better capture and analyse partial 
  and full return patterns

### Cost Optimisation
- Renegotiate pricing for medium-sized fast-delivery orders which carry the highest 
  average cost
- Consolidate smaller orders where possible to reduce unit cost and delivery frequency

### Warehouse Operations
- Rebalance inventory distribution across warehouse destinations to reduce pressure 
  on high-demand locations and improve fulfilment efficiency## Limitations
- Dataset does not capture real-time supplier performance updates
- Return status contains missing values which may affect defect analysis
- Analysis is limited to available order records and may not reflect full supply chain complexity
- Supplier location data is limited to country level only
  

## Limitations
- Dataset does not capture real-time supplier performance updates
- Return status contains missing values which may affect defect analysis
- Analysis is limited to available order records and may not reflect full supply chain complexity
- Supplier location data is limited to country level only

  
## Author
**Ugo Eke Ukonu**
[LinkedIn](http://www.linkedin.com/in/ukonu-ugoeke) | [Medium](https://medium.com/@ugoukonue)

## License
This project is licensed under the MIT License — see the LICENSE file for details.
