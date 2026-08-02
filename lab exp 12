import pandas as pd
import matplotlib.pyplot as plt

data = pd.read_csv("weather_data.csv")

plt.figure(figsize=(8,5))
plt.plot(data["Month"], data["Temperature"], marker='o')
plt.title("Monthly Temperature")
plt.xlabel("Month")
plt.ylabel("Temperature (°C)")
plt.grid(True)
plt.show()

plt.figure(figsize=(8,5))
plt.scatter(data["Month"], data["Rainfall"])
plt.title("Monthly Rainfall")
plt.xlabel("Month")
plt.ylabel("Rainfall (mm)")
plt.grid(True)
plt.show()
