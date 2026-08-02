import pandas as pd

# Sample DataFrame
order_data = pd.DataFrame({
    'Customer_ID': ['C101', 'C102', 'C101', 'C103', 'C102', 'C101'],
    'Order_Date': ['2025-01-10', '2025-01-12', '2025-01-15',
                   '2025-01-18', '2025-01-20', '2025-01-22'],
    'Product_Name': ['Laptop', 'Mouse', 'Laptop',
                     'Keyboard', 'Mouse', 'Keyboard'],
    'Order_Quantity': [2, 5, 1, 3, 2, 4]
})

# Convert Order_Date to datetime format
order_data['Order_Date'] = pd.to_datetime(order_data['Order_Date'])

# 1. Total number of orders made by each customer
print("1. Total Orders by Each Customer:")
print(order_data.groupby('Customer_ID').size())

# 2. Average order quantity for each product
print("\n2. Average Order Quantity for Each Product:")
print(order_data.groupby('Product_Name')['Order_Quantity'].mean())

# 3. Earliest and latest order dates
print("\n3. Earliest Order Date:")
print(order_data['Order_Date'].min())

print("\nLatest Order Date:")
print(order_data['Order_Date'].max())
