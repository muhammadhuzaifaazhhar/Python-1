# Python-1
# Problem 1: Item Quantity Pricing

# Get user input for quantity of an item
quantity = int(input("Enter the quantity of the item: "))

# Determine unit price based on quantity
if quantity >= 1000:
    unit_price = 3.00
else:
    unit_price = 5.00

# Calculate extended price, tax, and total
extended_price = quantity * unit_price
tax_rate = 0.07
tax = extended_price * tax_rate
total = extended_price + tax

# Display results
print(f"\nQuantity: {quantity}")
print(f"Unit Price: ${unit_price:.2f}")
print(f"Extended Price: ${extended_price:.2f}")
print(f"Tax: ${tax:.2f}")
print(f"Total: ${total:.2f}")
