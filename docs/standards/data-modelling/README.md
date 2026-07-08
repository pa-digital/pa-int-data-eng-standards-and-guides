# Data Modelling


## Purpose

Define how data should be structured across the platform to ensure consistency, maintainability, and ease of consumption.


## Why This Is Important

Good data modelling creates a common approach to organising data across teams. It improves usability, reduces complexity, supports governance, and makes data products easier to understand, maintain, and scale.


## Principles

- Use layered architecture (raw → bronze → silver → gold)
- Keep raw immutable
- Apply transformations incrementally
- Use consistent schemas

## Naming

- snake_case
- clear, descriptive entity names


## Good Example

A customer dataset follows a layered architecture:

```text
raw/customer_api/
bronze/customer/
silver/customer/
gold/customer_analytics/


## Bad Example 

Data is stored without a clear structure:

data/
customer_v2/
customer_final/

Naming is inconsistent:

CustID
CustomerName
dateCreated