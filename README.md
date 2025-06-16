# Streamlining Supply Chain Dynamics — Empowering Agriculture, Empowering Efficiency

## Project Highlights
- 🏆 **Winner of the 2025 Future Edelman Impact Award**
- Achieved a ~54% reduction in intercompany transfers and a ~3% reduction in total delivery distance
- Improved customer retention and reduced logistics costs through advanced analytics and optimization

---

## Project and Problem Statement Description
This project addresses significant inefficiencies in the distribution and fulfillment operations of a major North American seed manufacturer. The main challenges included:
- Excessive shipments: Customers received multiple fragmented deliveries for orders that could have been consolidated, leading to higher transportation costs and dissatisfaction.
- Frequent intercompany transfers: Warehouses regularly relied on transferring inventory between locations to meet demand, increasing operational complexity and causing delays.
- Inefficient warehouse-to-customer mapping: A static, one-to-one assignment of customers to warehouses led to longer delivery distances and suboptimal resource utilization.

These issues resulted in increased logistics costs, poor truck utilization, and declining customer retention—particularly during the critical peak sales season.

## Methodology and Solution Proposed
A structured, analytics-driven approach was used to address the supply chain inefficiencies:
- **Excessive Shipments**: Analyzed customer order patterns to identify fragmentation and its link to churn, with the aim of improving consolidation.
- **Intercompany Transfers**: Predicted inventory shortfalls and recommended proactive safety stock placement to reduce costly transfers.
- **Warehouse-to-Customer Mapping**: Used optimization to redesign delivery routes, aiming to minimize distance and transfer reliance.

### Technical Solution
- **Data Preparation**: Five years of historical data were processed, including shipment, inventory, transfer, production, and returns data. Key steps included missing value treatment, outlier removal, date alignment, and standardization of product and warehouse identifiers.
- **Excessive Shipments Analysis**: Defined and measured excess shipments, segmented customers, and created KPIs such as Excess Shipment %, Customer Retention Rate, and Minimum Shipments Required.
- **Intercompany Transfers**: Used Exponentially Weighted Moving Average (EWMA) to forecast shortfall ratios and recommend safety stock levels. Developed Tableau dashboards for risk identification.
- **Delivery Optimization**: Built a two-stage stochastic linear programming model to optimize warehouse-customer assignments and minimize transfers and delivery distances. Implemented in Python using PuLP, with outputs visualized in Tableau.

## Impact
- **Excessive Shipments**: Over 89% of customers received multiple shipments despite placing orders below truckload capacity, highlighting major consolidation opportunities. Customer retention rate dropped from over 99% to 85%, showing a strong negative correlation with shipment fragmentation.
- **Intercompany Transfers**: In the most recent year, over 60% of shipments were dependent on intercompany transfers. Safety stock planning and product prioritization reduced the need for transfers, resulting in an estimated reduction of ~304 truck trips annually (~7% of total trips).
- **Warehouse-to-Customer Mapping Optimization**: The optimization model suggested a ~54% reduction in product-level intercompany transfers and a ~3% reduction in total distance traveled, translating to lower fuel costs, better truck utilization, and improved delivery timelines.

## Challenges
- Data limitations required several assumptions.
- Lack of order-level data made it difficult to identify lead times.
- Formulating constraints for the optimization model was complex due to the exponential increase in model complexity.

## Recognition
This project was awarded the **2025 Future Edelman Impact Award**. More details about the award can be found at the [official website](https://business.purdue.edu/masters/programs/ms-business-analytics-and-information-management/experience/future-edelman.php).

## Project Poster
See the attached `ProjectPoster.pdf` for a visual summary of the project.

## Project Video
Watch the project video here: [YouTube Link](https://youtu.be/llBVkrbu4IE?si=B4YRfxdni7mXjWat)

---
*Note: Client and warehouse names have been masked in accordance with NDA requirements.* 