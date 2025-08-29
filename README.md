# 🛒 Discount Calculator

This Python program calculates the final price of an item after applying a discount.  
If the discount percentage is **20% or higher**, the discount is applied. Otherwise, the original price is returned.  

---

## 📌 Features
- Accepts original price and discount percentage as user input  
- Applies discount only if it’s **20% or more**  
- Returns the final price after applying the discount  
- Handles cases where no discount is applied  

---

## ⚙️ How It Works
1. The user is prompted to enter:
   - The **original price** of an item  
   - The **discount percentage**  
2. The program checks:
   - If `discount_percent >= 20` → applies the discount  
   - Else → keeps the original price  
3. The final price is printed.

---

## 💻 Example Usage

```bash
Enter the original price of the item: 1000
Enter the discount percentage: 25
Final price after 25% discount: 750.0
