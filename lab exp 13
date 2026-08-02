import pandas as pd
data = pd.read_csv("1stock_data.csv")

print("Stock Data")
print(data)

mean_price = data["ClosingPrice"].mean()
variance = data["ClosingPrice"].var()
std_dev = data["ClosingPrice"].std()

print("\nMean Closing Price =", mean_price)
print("Variance =", variance)
print("Standard Deviation =", std_dev)

if std_dev > 4:
    print("Insight: Stock prices show high variability.")
else:
    print("Insight: Stock prices show low variability.")
