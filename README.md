# Market Basket Analysis

**Market Basket Analysis(MBA)** is a data mining technique commonly used in retail industry to understand customer purchasing behavior by examining the relationships between products that are bought together. It involves analysing the transaction data to discover patterns in how products are grouped in customer purchases, which can help retailers make informed decisions about product placement, promotions, and inventory management.

## Key Concepts in Market Basket Analysis:
1. **Association Rules:** The main output of MBA is a set of rules showing which products are frequently purchased together. These rules take the form of "If customer buys X, they are likely to buy Y".
2. **Support:** This measures the proportion of transactions that include both item. For example, if 20% of all transactions include both bread and butter, the support for the rule {bread -> butter} is 20%.
3.**Confidence:** This measures the likelihood that a customer will purchase an item Y when they have already purchased item X. For example, if 50% of customers who buy bread also buy butter, the confidence of the rule {bread -> butter} is 50%.
4. **Lift**: Lift is the measure of the association between two items compared to if they were independent. A lift greater than 1 indicates a positive association (items are more likely to be purchased together), while a lift less than 1 indicates a negative association.

## Applications of Market Basket Analysis:
* Product Placement: Retailers can place related products near each other to encourage cross-selling.
* Promotions and Discounts: Retailers can bundle items that are frequently purchased together and offer discounts on them.
* Inventory Management: Knowing which products are frequently bought together helps in better managing stock and avoiding shortages.
* Personalised Recommendations: E-commerce platforms use MBA to recommend related products to customers based on their browsing or purchasing history.


