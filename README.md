# Credit-Card-Case-Study
### Summary of the Credit Card Case Study

#### **Analytics in the Credit Card Industry**
Credit card analytics plays a crucial role in understanding customer behavior, personalizing offerings, detecting fraud, and reducing chargebacks. Insights derived from data can help companies:
- Develop targeted marketing campaigns.
- Identify new customer acquisition opportunities.
- Uncover fraudulent transactions and reduce financial losses.
- Improve profitability through personalized financial products and services.

#### **Business Problem**
PSPD Bank operates globally and seeks data-driven insights to address issues like bankruptcy, fraud detection, collections, and customer relationship management. The CEO, Mr. Jim Watson, wants a consultant’s help in evaluating customer spending and repayment behaviors.

#### **Available Data**
The case study includes three datasets:
1. **Customer Acquisition**: Information collected at the time of issuing credit cards.
2. **Spend (Transaction Data)**: Customer credit card spending records.
3. **Repayment**: Credit card payment history of customers.

#### **Analysis Requirements**
1. **Data Cleaning**:
   - Replace age values below 18 with the mean age.
   - Cap spending amounts exceeding the credit limit to 50% of the customer’s limit.
   - Cap repayment amounts exceeding the credit limit to the limit itself.

2. **Summaries to be Created**:
   - Count of distinct customers and categories.
   - Average monthly spending and repayment.
   - Monthly profit for the bank using a 2.9% interest rate, where profit is the positive difference between repayment and spending.
   - Top 5 product types.
   - City with the highest spending.
   - Age group with the highest spending.
   - Top 10 customers by repayment amount.

3. **Graphical Analysis**:
   - City-wise yearly spending by product, with visual representations.
   - Monthly spending comparisons across cities.
   - Yearly comparison of air ticket spending.
   - Monthly spending comparisons by product to detect seasonality.

4. **User-Defined Python Function**:
   - Create a function to identify the top 10 customers in terms of repayment by product and time period (yearly or monthly). The function should accept user inputs for product type and time period.

#### **Deliverables**:
- Cleaned datasets.
- Summarized insights.
- Visualizations for specified comparisons.
- Python code with a user-defined function for dynamic analysis.
