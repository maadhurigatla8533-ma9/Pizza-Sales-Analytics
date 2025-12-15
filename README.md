# Pizza-Sales-Analytics
# 🍕 Pizza Sales Analysis Using SQL  
*(Unlocking Order Volumes & Revenue Insights)*  

## **Project Overview**  

This project employs SQL and MySQL Workbench to analyze a full year of **pizza sales data from the food service industry (2015)** to uncover insights on order volumes, revenue patterns, and customer ordering behavior. The aim is to provide actionable intelligence for the food service industry.  

---

## **Data Schema**  

**Tables:**  
- **order_details**: order_details_id, order_id, pizza_id, quantity  
- **orders**: order_id, date, time  
- **pizzas**: pizza_id, pizza_type_id, price, size  
- **pizza_types**: pizza_type_id, category, ingredients, name  

---

## **Key Results (2015)**  

**Totals**  
- **Total Orders**: 21,350  
- **Total Revenue**: $817,860  

**Key Performance Insights**  
- Highest Priced Pizza: *The Greek Pizza* ($35.95)  
- Most Popular Size: Large (18,526 units sold)  
- Busiest Order Hour: 18:00 (2,599 orders)  

**Pizza Categories by Quantity**  
- Classic: 14,838 units  
- Supreme: 11,697 units  
- Veggie: 11,439 units  
- Chicken: 10,050 units  

**Top 5 Pizzas by Quantity**  
1. The Classic Deluxe Pizza: 2,453  
2. The Barbecue Chicken Pizza: 2,432  
3. The Hawaiian Pizza: 2,422  
4. The Pepperoni Pizza: 2,418  
5. The Thai Chicken Pizza: 2,371  

**Top 3 Revenue-Generating Pizzas**  
1. The Thai Chicken Pizza: $43,481  
2. The Barbecue Chicken Pizza: $42,768  
3. The California Chicken Pizza: $41,409  

---

## **Methodology**  

- **Question-Led Design:** Targeted questions categorized into basic, intermediate, and advanced to mirror business BI priorities.  
- **Modular SQL:** CTEs for clarity and reuse; window functions for cumulative revenue and per-category rankings.  
- **Validation:** Cross-check of totals and rankings; separation of orders (transactions) versus quantity (units sold) for accurate messaging.  

---

## **Insights**  

- **Demand Concentration**  
  - Evening peak at 18:00 suggests strong dinner-time ordering behavior.  
  - Large size dominates quantity, indicating customer preference for group/value purchases.  

- **Product Mix**  
  - Classic category leads in units; chicken-based varieties feature heavily in revenue top ranks, balancing popularity with price.  

- **Revenue Drivers**  
  - A small set of pizzas (Thai Chicken, Barbecue Chicken, California Chicken) contribute outsized revenue—prime candidates for feature placement.  

- **Price Positioning**  
  - The Greek Pizza holds the highest price point, useful for premium upsell strategy.  

- **Category Breadth**  
  - Healthy spread across categories (Classic, Supreme, Veggie, Chicken) suggests a resilient menu with multiple demand anchors.  

---

## **Recommendations**  

- **Inventory and Prep**  
  - Stock and prep for Large size demand; prioritize Classic and high-revenue chicken variants during peak evening windows.  

- **Promotions and Menu Engineering**  
  - Spotlight top revenue items (Thai Chicken, Barbecue Chicken) with bundles or featured placements.  
  - Maintain a premium tier anchored by The Greek Pizza; test limited-time offers to support price elasticity and upsell.  

- **Peak-Hour Operations**  
  - Staff and kitchen readiness aligned to 18:00–20:00; use pre-batch prep for high runners to reduce wait times.  

- **Category Strategy**  
  - Protect Classic category volumes; selectively grow Veggie and Chicken with data-backed flavors that mirror top performers.  

- **Ongoing Monitoring**  
  - Weekly track: revenue by item, size mix, hourly orders; monthly review of top 10 items for menu optimization.  

---

## **Tools Used**  

- **MySQL Workbench**  
  - Query authoring and execution, schema exploration, and results validation.  
  - Utilized joins, GROUP BY, ORDER BY, LIMIT, Common Table Expressions (CTEs), and window functions for advanced analysis.  

- **Excel**  
  - Used for lightweight calculations and preparing exhibit-ready tables.  

- **Presentation Tools**  
  - PowerPoint/Google Slides to structure the 13-question narrative: one slide per question with the exact SQL and plain-English insight.  
  - Portfolio PDF export for sharing and archiving.  

---

## **What This Demonstrates**  

- Strong SQL fluency across joins, aggregation, CTEs, and window functions.  
- Ability to translate raw data into executive KPIs and operational guidance.  
- Clear, presentation-ready storytelling suitable for stakeholders and hiring managers.  
