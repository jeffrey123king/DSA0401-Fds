import pandas as pd

# Sample DataFrame
sales_data = pd.DataFrame({
    'Product_Name': ['Laptop', 'Mouse', 'Keyboard', 'Laptop',
                     'Mouse', 'Laptop', 'Keyboard', 'Monitor'],
    'Quantity_Sold': [5, 10, 8, 7, 6, 4, 9, 3]
})

# Find Top 5 Most Sold Products
top5_products = sales_data.groupby('Product_Name')['Quantity_Sold'].sum() \
                          .sort_values(ascending=False) \
                          .head(5)

print("Top 5 Most Sold Products:")
print(top5_products)
