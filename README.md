# Knowing_the_Customer
To identify our customers and explore all three datasets in the Data folder.

## Scenario
As a data analyst at Ebuy Emporium, a new e-commerce startup, the employer has developed an active interest in understanding their customer base. Key questions include:
- Who are their customers?
- What do they buy?
- What drives their purchasing behavior?

Before conducting any serious analysis, it is essential to count the customers accurately.

## Problem
There are multiple sources of customer data:
<<<<<<< HEAD
- **[E-commerce platform’s customer database](Knowing_the_Customer\Data\customer_database.csv)**: Records customer details when they sign up for an account online. This is where most customer details should be found.
- **In-house CRM (Customer Relationship Management) system**: Records customer details when they make a purchase over the phone or are otherwise onboarded as customers (excluding online purchases with a registered account).
- **[Raw transaction data](https://github.com/KhaingSuThway/Knowing_the_Customer/blob/4302be31b54275a773ea19efbe681c62f42c58dc/Data/purchases.csv)**: Referred to as “purchases” or “sales,” this data includes purchases made “as a guest,” meaning customer records are not explicitly created at the time of purchase.
=======
- **[E-commerce platform’s customer database](https://github.com/KhaingSuThway/Knowing_the_Customer/blob/bdbeb551901d60aa70766550ad3cd642985f5b93/Data/customer_database.csv)**: Records customer details when they sign up for an account online. This is where most customer details should be found.
- **[In-house CRM (Customer Relationship Management) system](https://github.com/KhaingSuThway/Knowing_the_Customer/blob/4302be31b54275a773ea19efbe681c62f42c58dc/Data/crm_export.csv)**: Records customer details when they make a purchase over the phone or are otherwise onboarded as customers (excluding online purchases with a registered account).
- **Raw transaction data**: Referred to as “purchases” or “sales,” this data includes purchases made “as a guest,” meaning customer records are not explicitly created at the time of purchase.
>>>>>>> 3f118bca73dffe1d691ce0831cb0bd24c28ddbe4

### Challenges
- **Overlapping Data Sources**: The existing data sources may not be mutually exclusive, leading to potential overlaps.
- **Duplication**: There is almost certainly some duplication, either because the same customer had their details entered into multiple systems or because they have made purchases both as a guest and with a registered account.
- **Inconsistent Information**: Duplicate accounts may not contain exactly the same information due to typos or misspellings.

These complications necessitate the help of an analyst to answer the question: “Who are our customers?”

## Final Output
A dataset containing one row per "inferred customer entity."
