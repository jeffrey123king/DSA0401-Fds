import pandas as pd
import matplotlib.pyplot as plt

# Read the CSV file
sales_data = pd.read_csv("monthly_sales.csv")

# Display the dataset
print("Monthly Sales Data")
print(sales_data)

# ---------------- Line Plot ----------------
plt.figure(figsize=(8,5))
plt.plot(sales_data["Month"], sales_data["Sales"], marker='o', linewidth=2)
plt.title("Monthly Sales - Line Plot")
plt.xlabel("Month")
plt.ylabel("Sales")
plt.grid(True)
plt.show()

# ---------------- Scatter Plot ----------------
plt.figure(figsize=(8,5))
plt.scatter(sales_data["Month"], sales_data["Sales"])
plt.title("Monthly Sales - Scatter Plot")
plt.xlabel("Month")
plt.ylabel("Sales")
plt.grid(True)
plt.show()

# ---------------- Bar Plot ----------------
plt.figure(figsize=(8,5))
plt.bar(sales_data["Month"], sales_data["Sales"])
plt.title("Monthly Sales - Bar Plot")
plt.xlabel("Month")
plt.ylabel("Sales")
plt.show()
