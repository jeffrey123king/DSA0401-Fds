import numpy as np
n = int(input("Enter the number of items: "))

prices = []
quantities = []

for i in range(n):
    price = float(input(f"Enter price of item {i+1}: "))
    quantity = int(input(f"Enter quantity of item {i+1}: "))

    prices.append(price)
    quantities.append(quantity)

prices = np.array(prices)
quantities = np.array(quantities)

discount_rate = float(input("Enter discount rate (%): "))
tax_rate = float(input("Enter tax rate (%): "))

subtotal = np.sum(prices * quantities)

discount = subtotal * (discount_rate / 100)

price_after_discount = subtotal - discount

tax = price_after_discount * (tax_rate / 100)

total_cost = price_after_discount + tax

print("Subtotal:", subtotal)
print("Discount:", discount)
print("Tax:", tax)
print("Total Cost:", total_cost)
