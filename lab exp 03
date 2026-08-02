import numpy as np

# Columns: Bedrooms, Square Footage, Sale Price
house_data = np.array([
    [3, 1200, 250000],
    [5, 2000, 450000],
    [4, 1800, 350000],
    [6, 2500, 550000],
    [5, 2200, 500000]
])

# Select houses with more than 4 bedrooms
houses = house_data[house_data[:, 0] > 4]

# Calculate average sale price
average_price = np.mean(houses[:, 2])

print("Houses with more than 4 bedrooms:")
print(houses)

print("\nAverage Sale Price =", average_price)
