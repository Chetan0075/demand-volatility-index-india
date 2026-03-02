## Orders Data Cleaning
- No duplicate order IDs found
- No missing values detected
- Converted order_date to monthly granularity (YYYY-MM)
- Standardized shipping_country text format


## Order Items Data Cleaning
- No duplicate order_item_id found
- Removed rows with non-positive quantity or unit_price
- Created item_sales column at transaction level


## Products Data Cleaning
- Verified unique product_id with no duplicates
- No missing or invalid price values detected
- Standardized text fields for consistency
- Preserved original category structure (6 categories)

## Customers cleaning complete
- changed date format form dd mm yyyy to yyyy-mm-dd

