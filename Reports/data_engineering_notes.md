## Orders Data Cleaning
- No duplicate order IDs found
- No missing values detected
- Converted order_date to monthly granularity (YYYY-MM)
- Standardized shipping_country text format


## Order Items Data Cleaning
- No duplicate order_item_id found
- Removed rows with non-positive quantity or unit_price
- Created item_sales column at transaction level
