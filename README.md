# Customer-Retention-Product-Recommendation-Revenue-Optimization
Apriori Algorithm and RFM analysis 

# REPORT 

Kenya Customers | Kenya Deliveries | Kenya Orders | Nigeria Customers | Nigeria deliveries | Nigeria Orders datasets 
are merged into a single file and uploaded as Merged File with 22633 rows * 42 columns .
Dropped 20 columns with null values which does not contribute to the solution of this problem statement

Final shape of the dataframe is 22633 rows * 22 columns

# Apiriori Algorithm 

used to derive insights from data by finding the confidence ,support and lift which is useful for market analysis.

Package used for Apirirori is mlxtend.frequent_patterns
   
# Product Recommendation 

Finding Antecedents and Consequents which are product recommendations used for cross selling based on confidence,support and lift 

# Plots 

Scatter plot to evaluate Antecedent and Consequent and Pie Chart for customer segmentation
   
# Customer Retention,Classify Customers,Revenue Optimization 

RFM analysis used
   
# RFM analysis

Recency: How recently has the customer made a transaction with us

Frequency: How frequent is the customer in ordering/buying some product from us

Monetary: How much does the customer spend on purchasing products from us.

Customer ID / Customers are displayed by ranking customers based on their RFM score
    
    rfm score>4.5       : Top Customer
    4.5 > rfm score > 4 : High Value Customer
    4 >rfm score >3     : Medium value customer
    3 >rfm score >1.6   : Low-value customer
    rfm score<1.6       : Lowest value Customer

# Revenue Optimization 
Net revenue calculated with the given formula 

Net Revenue = Number of customers * Average Order Frequency * Average Order Value * Gross Margin %
            
            = 550 * 22.241 * 11066.63 * 3
            = 406096195

# 406096195 KSh
