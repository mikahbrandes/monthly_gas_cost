# monthly_gas_cost
This is a tool for me to see how much it'll cost me in gas each month depending on the total miles I plan to drive.
# Inputs
monthly_miles = 960  # miles per month
tank_capacity = 18   # gallons
gas_price = 3.25     # dollars per gallon
fuel_efficiency = 19  # miles per gallon

# Calculate total gallons of gas needed
gallons_needed = monthly_miles / fuel_efficiency

# Calculate total cost of gas
total_gas_cost = gallons_needed * gas_price

# Display results
print("\n--- Gas Cost Calculation ---")
print(f"Monthly miles driven: {monthly_miles} miles")
print(f"Fuel efficiency: {fuel_efficiency} mpg")
print(f"Gas price: ${gas_price:.2f} per gallon")
print(f"Gallons of gas needed: {gallons_needed:.2f} gallons")
print(f"Total monthly gas cost: ${total_gas_cost:.2f}")

--- Gas Cost Calculation ---
Monthly miles driven: 960 miles
Fuel efficiency: 19 mpg
Gas price: $3.25 per gallon
Gallons of gas needed: 50.53 gallons
Total monthly gas cost: $164.21
