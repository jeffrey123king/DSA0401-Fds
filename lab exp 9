import pandas as pd

# Create the DataFrame
property_data = pd.DataFrame({
    'Property_ID': ['P101', 'P102', 'P103', 'P104', 'P105'],
    'Location': ['Chennai', 'Coimbatore', 'Chennai', 'Madurai', 'Coimbatore'],
    'Bedrooms': [3, 5, 4, 6, 2],
    'Area_sqft': [1500, 2200, 1800, 2500, 1400],
    'Listing_Price': [7500000, 9500000, 8200000, 12000000, 6800000]
})

# 1. Average listing price of properties in each location
print("1. Average Listing Price in Each Location:")
print(property_data.groupby('Location')['Listing_Price'].mean())

# 2. Number of properties with more than four bedrooms
count = property_data[property_data['Bedrooms'] > 4].shape[0]
print("\n2. Number of Properties with More Than Four Bedrooms:")
print(count)

# 3. Property with the largest area
largest_property = property_data.loc[property_data['Area_sqft'].idxmax()]
print("\n3. Property with the Largest Area:")
print(largest_property)
