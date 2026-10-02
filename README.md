# Customer-Behavior-Analysis-
An end-to-end customer analytics project transforming transactional data into actionable business insights using Python, PostgreSQL, SQL, and Power BI.
<img width="1174" height="639" alt="image" src="https://github.com/user-attachments/assets/54b73c87-457c-4fde-9d64-45b3dcd14a16" />

---
🎯 Business Objective

The goal of this project is to understand how customers shop, what they purchase, how discounts and subscriptions influence behavior, and which customer/product groups contribute to revenue.

The analysis is designed to answer questions such as:

Which customer groups generate the most revenue?
How does spending differ between subscribers and non-subscribers?
Which products receive the highest ratings?
Which products are most dependent on discounts?
Are repeat customers more likely to subscribe?
Which age groups contribute the most revenue?
How does shipping type relate to purchase value?

---
🐍 1. Data Cleaning & Exploratory Data Analysis

Python was used to prepare the dataset for analysis.

Data Preparation
Loaded the dataset using Pandas
Inspected the dataset structure using df.info()
Generated descriptive statistics using df.describe()
Identified missing values
Imputed missing Review Rating values using the median rating by product category
Standardized column names using snake_case
Checked consistency between discount_applied and promo_code_used
Removed the redundant promo_code_used column
Feature Engineering

Two additional analytical features were created:

age_group
purchase_frequency_days

The cleaned dataset was subsequently loaded into PostgreSQL for structured SQL analysis.

---
🗄️ 2. SQL Business Analysis

PostgreSQL was used to answer 10 business-focused questions.

🔍 Analysis Areas
#	Business Question
01	Revenue by Gender
02	High-Spending Discount Users
03	Top 5 Products by Rating
04	Standard vs. Express Shipping
05	Subscribers vs. Non-Subscribers
06	Products Most Dependent on Discounts
07	Customer Segmentation
08	Top 3 Products by Category
09	Repeat Buyers & Subscription Behavior
10	Revenue by Age Group

These analyses cover revenue, customer behavior, product performance, discounts, subscriptions, shipping, and demographics.

---
📈 3. Power BI Dashboard

The cleaned and analyzed data was brought into Power BI to create an interactive dashboard.

Dashboard Focus

The dashboard provides visual analysis of:

👥 Customer Behavior

Customer segments
Purchase frequency
Previous purchases
Demographics

💰 Revenue

Revenue contribution
Average purchase behavior
Revenue by demographic groups

🛍️ Product Performance

Best-selling products
Product categories
Product ratings

🎟️ Discounts

Discount usage
Discount-dependent products
High-spending discount users

⭐ Subscriptions

Subscriber vs. non-subscriber behavior
Repeat buyers and subscription behavior

🚚 Shipping

Standard vs. Express shipping
Purchase-value comparison

---
💡 Business Insights & Recommendations

The analysis resulted in several business recommendations:

🔔 Subscription Growth

Promote exclusive benefits and incentives to encourage subscription adoption.

❤️ Customer Loyalty

Reward repeat buyers and encourage progression toward the Loyal customer segment.

🏷️ Discount Optimization

Review discount strategies to balance sales stimulation with margin control.

⭐ Product Positioning

Use highly rated and best-selling products in marketing campaigns.

🎯 Targeted Marketing

Focus marketing efforts on high-revenue age groups and customers associated with express shipping.

---
🛠️ Tech Stack
Technology	Role
🐍 Python	Data cleaning & exploratory analysis
🐼 Pandas	Data manipulation
🗄️ PostgreSQL	Database & data storage
🔎 SQL	Business analysis
📊 Power BI	Dashboard & visualization
