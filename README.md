# Basket Analysis Project

This project performs a **Market Basket Analysis (MBA)** using transaction data to uncover relationships between products purchased together. It provides insights into customer buying patterns, helping businesses optimize cross-selling strategies and product placement.

## Overview

- **Total Transactions:** 7,835  
- **Unique Products:** 170  
- **Key Objective:** Identify product combinations frequently purchased together to optimize store layout, promotions, and product bundling.

### Key Components

1. **Basket Analysis Network**  
   - Visualizes relationships between products.
   - Nodes represent products; edges show associations between them.
   - Node size indicates product frequency in transactions.
   - Example:
     - *Yogurt* (14.4%) and *Root Vegetables* (14.1%) show strong associations.
     - *Whipped/Sour Cream* (13.7%) also demonstrates high connectivity with other products.

2. **Basket Analysis Map**  
   - Scatter plot showing product associations.
   - X-axis: **Lift** - measures how much more often two products are bought together compared to being bought independently.
   - Y-axis: **Support** - the frequency of transactions containing the product pair.

3. **Basket Analysis Details**  
   - Tabular summary of product pairs and their metrics:
     - **Support**: Frequency of the pair being bought together.
     - **Confidence**: Likelihood of a product being purchased given another product is bought.
     - **Lift**: Strength of the association between products.

---

## Features

- **Interactive Network Graph**: Explore product relationships and their strength visually.
- **Lift and Confidence Metrics**: Quantify the significance of associations.
- **Product Pair Rankings**: Identify the most influential combinations for promotions.

---

## Technologies Used

- **Data Processing**: Python (Pandas, NumPy)
- **Visualization**: Power BI (Dashboard with charts, network graphs, and tables)
- **Association Rule Mining**: Apriori algorithm

## Insights & Business Recommendations

### Insights
1. **Frequently Purchased Together**:
   - *Yogurt* and *Soft Cheese* have a strong association with a high confidence value of 37.4%.

![image](https://github.com/user-attachments/assets/8c6b0bf2-f708-4ecd-afb8-443bf214c8f9)


   - *Root Vegetables* are frequently paired with other vegetables, indicating a natural grouping in purchases.

2. **High-Lift Product Pairs**:
   - *Whipped/Sour Cream* and *Curd* show a high lift value, suggesting a strong relationship.

![image](https://github.com/user-attachments/assets/310ae90d-1b5c-42ec-8468-709962997da2)

  
 - *Root Vegetables* and *Herbs* also have a high lift, recommending closer placement in stores.

3. **Product Popularity**:
   - *Yogurt*, *Root Vegetables*, and *Whipped/Sour Cream* are among the most purchased items, representing key drivers of sales.

---

### Business Recommendations
1. **Promotional Strategies**:
   - Create product bundles for highly associated items (e.g., *Yogurt* and *Soft Cheese*) to boost sales.
   - Offer discounts or promotions for complementary products like *Root Vegetables* and *Herbs*.

2. **Store Layout Optimization**:
   - Position strongly associated items near each other:
     - Place *Whipped/Sour Cream* and *Curd* in adjacent shelves.
     - Group *Root Vegetables* with other vegetables and herbs.

3. **Cross-Selling Opportunities**:
   - Use high-confidence pairs (*Yogurt → Soft Cheese*) for targeted cross-selling campaigns.
   - Implement product recommendations on e-commerce platforms to suggest complementary items.

4. **Inventory Planning**:
   - Maintain sufficient stock for top products (*Yogurt*, *Root Vegetables*, *Whipped/Sour Cream*) to meet demand and avoid stockouts.

5. **Customer Engagement**:
   - Utilize loyalty programs to promote highly associated product pairs.
   - Personalize offers based on customer purchase history to increase basket size.



