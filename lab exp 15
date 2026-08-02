import pandas as pd
data = pd.read_csv("temperature_data.csv")
# Set City as index
data = data.set_index("City")
mean_temp = data.mean(axis=1)
std_temp = data.std(axis=1)
temp_range = data.max(axis=1) - data.min(axis=1)
print("Mean Temperature of Each City:")
print(mean_temp)
print("\nStandard Deviation of Each City:")
print(std_temp)
print("\nTemperature Range of Each City:")
print(temp_range)
# City with highest range
highest_range_city = temp_range.idxmax()
# City with lowest standard deviation
consistent_city = std_temp.idxmin()
print("\nCity with Highest Temperature Range:", highest_range_city)
print("City with Most Consistent Temperature:", consistent_city)
