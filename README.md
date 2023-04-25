# Customer Shopping Analysis
This is an exploratory data analysis on shopping data across malls in Instabul gotten from kaggle. The dataset can be downloaded from [here](https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset).

## Introduction
Welcome to the shopping world of Istanbul! Our dataset contains shopping information from 10 different shopping malls between 2021 and 2023. We have gathered data from various age groups and genders to provide a comprehensive view of shopping habits in Istanbul. The dataset includes essential information such as invoice numbers, customer IDs, age, gender, payment methods, product categories, quantity, price, order dates, and shopping mall locations. We hope that this dataset will serve as a valuable resource for researchers, data analysts, and machine learning enthusiasts who want to gain insights into shopping trends and patterns in Istanbul. Explore the dataset and discover the fascinating world of Istanbul shopping!

### Data
Attribute Information:

invoice_no: Invoice number. Nominal. A combination of the letter 'I' and a 6-digit integer uniquely assigned to each operation.
customer_id: Customer number. Nominal. A combination of the letter 'C' and a 6-digit integer uniquely assigned to each operation.
gender: String variable of the customer's gender.
age: Positive Integer variable of the customers age.
category: String variable of the category of the purchased product.
quantity: The quantities of each product (item) per transaction. Numeric.
price: Unit price. Numeric. Product price per unit in Turkish Liras (TL).
payment_method: String variable of the payment method (cash, credit card or debit card) used for the transaction.
invoice_date: Invoice date. The day when a transaction was generated.
shopping_mall: String variable of the name of the shopping mall where the transaction was made.

## Data Inspection and Cleaning
Upon inspection of the dataset, the following are the observations and data cleaning processes carried out on each column;
1. There were 99,458 transactions made with no duplicate records found.
2. Every invoice_no and customer_id record was unique.
3. Gender column only consisted of male and female entries.
4. Age of customers ranged from 18-69.
5. There were 8 product categories which are books,clothing, cosmetics, food & beverages, shoes, souvenir, technology and toys.
6. Quantity and Price were both positive numeric columns.
7. Payment method consists of cash,credit card or debit card.
8. Invoice date had inconsistent formating which was corrected to be in D/MM/YYYY format. Transactions ranged from January 2020 to December 2023.
9. There are only 10 malls include in the shopping_malls column.

