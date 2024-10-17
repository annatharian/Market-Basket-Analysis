# Market Basket Analysis

**Market Basket Analysis(MBA)** is a data mining technique commonly used in retail industry to understand customer purchasing behavior by examining the relationships between products that are bought together. It involves analysing the transaction data to discover patterns in how products are grouped in customer purchases, which can help retailers make informed decisions about product placement, promotions, and inventory management. We can further classify the item sets which are frequently bought by consumers using the Apriori Algorithm. The 3 main components of this algorithm are support, confidence and lift.

## Key Concepts in Market Basket Analysis:
1. **Association Rules:** The main output of MBA is a set of rules showing which products are frequently purchased together. These rules take the form of "If customer buys X, they are likely to buy Y".
2. **Support:** This measures the proportion of transactions that include both item. For example, if 20% of all transactions include both bread and butter, the support for the rule {bread -> butter} is 20%. Support = freq(X,Y)/N
3. **Confidence:** This measures the likelihood that a customer will purchase an item Y when they have already purchased item X. For example, if 50% of customers who buy bread also buy butter, the confidence of the rule {bread -> butter} is 50%. Confidence = freq(XY)/freq(X)
4. **Lift**: Lift is the measure of the association between two items compared to if they were independent. A lift greater than 1 indicates a positive association (items are more likely to be purchased together), while a lift less than 1 indicates a negative association. Lift = confidence%/support%

## There are 3 types of Market Basket Analysis:
1. **Descriptive:** This analysis identifies patterns and connections in the data between various items in a basket. Mostly used to understand customer behavior.
2. **Predictive:** Predicts future purchases based on patterns in past purchases. Makes use of machine learning algorithms to make data-driven decisions like how to price items, optimise shop layout and so on.
3. **Differential:** Analyses two sets of market basket data to understand the variations between them. This is used to compare the behaviors of various customers over time to modify markting and sales tactics.  

## Applications of Market Basket Analysis:
* Product Placement: Retailers can place related products near each other to encourage cross-selling.
* Promotions and Discounts: Retailers can bundle items that are frequently purchased together and offer discounts on them.
* Inventory Management: Knowing which products are frequently bought together helps in better managing stock and avoiding shortages.
* Personalised Recommendations: E-commerce platforms use MBA to recommend related products to customers based on their browsing or purchasing history.





