# python-challenge-1
Homework 2 : ChatGPT was utilized for debugging and creating README file

# Variety Food Truck Ordering System

This program simulates a simple ordering system for a variety food truck. It allows users to view a menu, select items to order, specify quantities, and displays the order total.

## Features

- **Multi-level Menu:** The menu is organized into categories (Snacks, Meals, Drinks, and Dessert), each containing various items, some with subcategories (e.g., types of pizza and sizes of drinks).
- **Dynamic Ordering:** Customers can choose items from different categories, specify quantities, and add multiple items to their order.
- **Order Summary:** Displays the ordered items with individual prices, quantities, and a total cost.

## Menu Structure

The menu includes the following categories and items:

### Snacks
- Cookie - $0.99
- Banana - $0.69
- Apple - $0.49
- Granola bar - $1.99

### Meals
- Burrito - $4.49
- Teriyaki Chicken - $9.99
- Sushi - $7.49
- Pad Thai - $6.99
- Pizza (Cheese - $8.99, Pepperoni - $10.99, Vegetarian - $9.99)
- Burger (Chicken - $7.49, Beef - $8.49)

### Drinks
- Soda (Small - $1.99, Medium - $2.49, Large - $2.99)
- Tea (Green - $2.49, Thai iced - $3.99, Irish breakfast - $2.49)
- Coffee (Espresso - $2.99, Flat white - $2.99, Iced - $3.49)

### Dessert
- Chocolate lava cake - $10.99
- Cheesecake (New York - $4.99, Strawberry - $6.49)
- Australian Pavlova - $9.99
- Rice pudding - $4.99
- Fried banana - $4.49

## Usage Instructions

1. **Launch the Program:** Run the script to start the food truck ordering system.
2. **Select a Category:** The program will display menu categories (Snacks, Meals, Drinks, Dessert). Choose a category by entering its number.
3. **Choose an Item:** Once a category is selected, a list of items in that category appears. Enter the item number to add it to your order.
4. **Specify Quantity:** Enter the quantity of the selected item you wish to order.
5. **Add More Items:** The program will ask if you want to continue ordering. Enter "Y" for Yes or "N" for No.
6. **Order Summary:** When finished, the program displays an order summary with item names, prices, quantities, and a total cost.

## Example

```
Welcome to the variety food truck.
From which menu would you like to order?
1: Snacks
2: Meals
3: Drinks
4: Dessert
Type menu number: 2
You selected Meals
What Meals item would you like to order?
Item # | Item name                | Price
-------|--------------------------|-------
1      | Burrito                  | $4.49
2      | Teriyaki Chicken         | $9.99
3      | Sushi                    | $7.49
...

Enter the item number you'd like to order: 3
Enter how many you would like: 2
Would you like to keep ordering? (Y)es or (N)o: N
Thanks for your order!

This is what we are preparing for you.
Item name                 | Price  | Quantity
--------------------------|--------|----------
Sushi                     | $7.49  | 2
Your order total is $14.98
```

## Code Overview

- **Menu Dictionary**: The `menu` dictionary contains all available items categorized by types (Snacks, Meals, etc.), with specific items and prices.
- **Order List**: An `order` list stores selected items as dictionaries containing item name, price, and quantity.
- **User Interaction**: The program guides the user through category selection, item choice, and quantity input with structured prompts and error handling.
- **Order Summary Calculation**: The total order cost is calculated by multiplying item prices by their quantities.

## Requirements

- Python 3.x

