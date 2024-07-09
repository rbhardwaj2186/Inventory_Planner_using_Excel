
# Inventory Data Analysis

This project provides an analysis of inventory data, focusing on different categories of products, their availability, demand, and inventory policies. The goal is to manage inventory effectively by analyzing key metrics and implementing appropriate inventory policies.
Table of Contents

    Inventory Data
    Inventory Policies
    Usage
    Contributing
    License

Inventory Data

The inventory data includes various categories of products, their SKU (Stock Keeping Unit), whether they are perishable or non-perishable, their availability, demand, demand type, and inventory type. The data also calculates the difference between availability and demand, as well as the demand-to-availability ratio.
Category	SKU	Perish/Non-Perish	Available	Demand	Demand Type	Available - Demand	Dmnd/Available	Inv Type
Fresh Packaged	FP2020	Non-Perishable	4063	4493	HIGH	-430	-11%	
Healthy Beverage	HB1016	Non-Perishable	4974	2578	HIGH	2396	48%	
Fresh Packaged	FP3055	Non-Perishable	2032	2574	HIGH	-542	-27%	
Meat	OP8025	Perishable	2073	2424	HIGH	-351	-17%	
Fish	OY2545	Perishable	4250	1795	HIGH	2455	58%	
Rice	HT2054	Non-Perishable	350	410	LOW	-60	-17%	
Organic Frozen	OF1060	Perishable	420	367	LOW	53	13%	
Organic Baby	OB1265	Perishable	130	346	LOW	-216	-166%	
Organic Frozen	OF2035	Perishable	358	316	LOW	42	12%	
Pickle	HT1064	Non-Perishable	438	301	LOW	137	31%	
Wheat	HT1045	Non-Perishable	294	285	LOW	9	3%	
Healthy Beverage	HB0156	Non-Perishable	331	212	LOW	119	36%	
Inventory Policies
Maintain Safety Stock and Implement FIFO

    Description: This policy involves keeping a buffer stock of inventory to mitigate the risk of stockouts due to unexpected increases in demand or supply chain disruptions. Additionally, it incorporates the First-In, First-Out (FIFO) method, ensuring that older inventory items are sold or used first, minimizing the risk of spoilage or obsolescence.
    Criteria:
        Overstock: > 25%
        Optimal: -5% to 25%
        Stockout: < -5%

Establish Reorder Point and Use EOQ

    Description: This strategy sets a predefined reorder point for inventory. When the stock level reaches this point, new orders are triggered to replenish supplies. It pairs with the Economic Order Quantity (EOQ) model, which calculates the optimal order quantity to minimize carrying costs and order costs, ensuring efficient inventory management.

Adopt JIT

    Description: Just-In-Time (JIT) is a lean inventory strategy aimed at minimizing inventory holding costs. It involves receiving goods only as needed, reducing excess inventory levels. This approach promotes efficiency by aligning production or procurement with actual demand, reducing storage costs and waste.

Implement Min-Max

    Description: Min-Max, or Minimum-Maximum, inventory policy sets a minimum and maximum stock level for each item. When the inventory falls to the minimum level, a reorder is triggered to bring it back to the maximum level. This approach helps maintain a consistent inventory level while minimizing excess stock.
