# 📖 Data Dictionary

This document describes the datasets used in the Power BI project.

---

# Sales

Stores each product sold through physical stores or the online channel.

| Field | Description |
|------|-------------|
| Order Number | Unique purchase order identifier |
| Line Item | Product line within the order |
| Order Date | Date the order was placed |
| Delivery Date | Delivery date (online sales only) |
| Customer_ID | Customer identifier |
| Store_ID | Store identifier (0 = Online Store) |
| Prod_Key | Product identifier |
| Quantity | Units sold |
| Currency Code | Currency used in the transaction |

---

# Customers

Contains demographic information about each customer.

| Field | Description |
|------|-------------|
| Customer_ID | Customer identifier |
| Gender | Customer gender |
| Name | Full name |
| City | City |
| State Code | State code |
| State | State or province |
| Zip Code | Postal code |
| Country | Country |
| Continent | Continent |
| Birthday | Birth date |

---

# Products

Product catalog information.

| Field | Description |
|------|-------------|
| Prod_Key | Product identifier |
| Product Name | Product name |
| Brand | Brand |
| Color | Product color |
| Unit Cost USD | Unit production cost |
| Unit Price USD | Retail price |
| SubcategoryKey | Subcategory identifier |
| Subcategory | Product subcategory |
| CategoryKey | Category identifier |
| Category | Product category |

---

# Stores

Information about physical stores and the online sales channel.

| Field | Description |
|------|-------------|
| Store_ID | Store identifier (0 = Online) |
| Country | Store country |
| State | Store state or region |
| Square Meters | Store size |
| Open Date | Store opening date |

---

# Exchange Rates

Daily exchange rates used for international sales.

| Field | Description |
|------|-------------|
| Date | Exchange rate date |
| Currency | Currency code |
| Exchange | Exchange rate relative to USD |
