## Discount Calculator

## Overview
This is a simple Python program that calculates the final price of an item after applying a discount.  
If the discount percentage is **20% or higher**, the discount is applied.  
If the discount percentage is **less than 20%**, the original price is returned without changes.

---

## How It Works
1. The program defines a function `calculate_discount(price, discount_percent)`.
2. The function checks the discount percentage:
   - If `discount_percent >= 20`: it applies the discount.
   - Otherwise: it returns the original price.
3. The user is prompted to enter:
   - The original price of the item.
   - The discount percentage.
4. The program prints the final price after applying the rules.
