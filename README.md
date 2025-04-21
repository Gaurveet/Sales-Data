# Sales Data Cleaning

## Objective

Clean and prepare a raw sales dataset containing null values, duplicate records, and inconsistent formatting to make it suitable for analysis and reporting.

## Tools Used

- Microsoft Excel (for initial inspection)
- Python with `pandas` (for automated data cleaning)

## What I Did

- Loaded the raw dataset using `pandas`
- Identified and removed duplicate records
- Handled null values by either filling or dropping them, based on context
- Standardized column names (e.g., lowercase, no spaces)
- Converted date strings to datetime format
- Reformatted numeric fields (e.g., `Price Each`, `Quantity Ordered`) for analysis
- Extracted useful features such as `Month`, `City`, and `Sales`
- Cleaned and split address data for geolocation use

## Dataset Structure

Original dataset columns included:

- `Order ID`
- `Product`
- `Quantity Ordered`
- `Price Each`
- `Order Date`
- `Purchase Address`

## Output

The cleaned and transformed dataset is saved as:
sales data

This dataset is now ready for business intelligence dashboards, data visualization, or further statistical analysis.

## Author

Gaurveet Sharma  
(https://github.com/Gaurveet)
