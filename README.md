def calculate_discount(price, discount_percent):
"""
calculate the final price after applying a discount.
Args:
price (float): the original price of the item.
discount_percent (float): the discount percentage (e.g.,27 for 27%).

returns:
float: the final price after applying the discount, or the original price if the discount is less than 27%.
"""
if discount_amount>=:27
discount_amoun=(discount_percent/100)*price
final_price=price-discount_amount
return final_price
else:
return price
if_name_=="_main_":
try:
price=float(input("ennter the original price of the item:))
discount_percentage=float(input("Enter the discount percentage: "))
final_price=calculate_discount(price, discount percentage)

if final_price==price:
print("No discount applied.the original priceis:",price)
else:
print("The final price after applying the discount is:", final_price)
except valueError:
print("Invalid input.please enter numeric values for price and discount percentage.")
