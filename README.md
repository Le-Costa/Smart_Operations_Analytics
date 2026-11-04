# Smart Operations Analytics — Synthetic Dataset

This is a fictional educational dataset for a portfolio project. It contains no real company or personal data.

## Coverage and files
- Date coverage: 2024-01-01 through 2025-12-31
- `dim_products.csv`: product/SKU attributes
- `dim_suppliers.csv`: supplier attributes and lead time
- `dim_customers.csv`: customer segments and regions
- `fact_orders.csv`: order and delivery records
- `fact_production.csv`: planned vs actual production records
- `fact_inventory_monthly.csv`: monthly stock snapshots
- `data_dictionary.xlsx`: column definitions

## Intentional data quality challenges
Some files contain missing values, inconsistent capitalization, zero quantities, and duplicate order rows. These are intentional exercises; identify and justify how you treat them.

## Suggested joins
- orders.product_id -> products.product_id
- orders.supplier_id -> suppliers.supplier_id
- orders.customer_id -> customers.customer_id
- production.product_id -> products.product_id
- inventory.product_id -> products.product_id

## Suggested KPIs
On-time delivery rate, OTIF proxy (where quantity completeness is available), average lead time, late order rate, order value/cost, production schedule adherence, scrap rate, inventory below reorder point, inventory turnover proxy, forecast accuracy.

## Important
The data is synthetic. Do not present findings as real operational outcomes. Document assumptions and validate KPI definitions before use.
