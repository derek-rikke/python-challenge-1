# Variety Food Truck Ordering System

This Python program is a simple command-line ordering system for the Variety Food Truck. It allows customers to select items from a menu, specify the quantity they want to order, and provides a summary of their order with the total cost.

## Menu Dictionary

The program uses a menu dictionary to store various food and drink options. The menu is structured hierarchically into categories, and each item has a name and a price associated with it.

```python
# Menu dictionary
menu = {
    "Snacks": {
        "Cookie": 0.99,
        "Banana": 0.69,
        "Apple": 0.49,
        "Granola bar": 1.99
    },
    "Meals": {
        "Burrito": 4.49,
        "Teriyaki Chicken": 9.99,
        "Sushi": 7.49,
        "Pad Thai": 6.99,
        "Pizza": {
            "Cheese": 8.99,
            "Pepperoni": 10.99,
            "Vegetarian": 9.99
        },
        "Burger": {
            "Chicken": 7.49,
            "Beef": 8.49
        }
    },
    "Drinks": {
        "Soda": {
            "Small": 1.99,
            "Medium": 2.49,
            "Large": 2.99
        },
        "Tea": {
            "Green": 2.49,
            "Thai iced": 3.99,
            "Irish breakfast": 2.49
        },
        "Coffee": {
            "Espresso": 2.99,
            "Flat white": 2.99,
            "Iced": 3.49
        }
    },
    "Dessert": {
        "Chocolate lava cake": 10.99,
        "Cheesecake": {
            "New York": 4.99,
            "Strawberry": 6.49
        },
        "Australian Pavlova": 9.99,
        "Rice pudding": 4.99,
        "Fried banana": 4.49
    }
}
```

## Ordering Process

1. Set up an empty order list to store the customer's selected items.

2. Launch the store and greet the customer with "Welcome to the Variety Food Truck."

3. Start a loop to allow the customer to place multiple orders.

4. The customer is prompted to select a menu category (e.g., Snacks, Meals, Drinks, Dessert).

5. Once a category is selected, the program lists the available items within that category.

6. The customer is prompted to input the number of the item they want to order.

7. After selecting an item, the program asks for the quantity of that item.

8. The selected item, its price, and the quantity are added to the order list.

9. The customer is asked if they want to order more items, and the process repeats.

10. When the customer is done ordering, a summary of their order is displayed, including item names, prices, and quantities.

11. The total cost of the order is calculated, and the final price is displayed.

## Running the Program

You can run this Python program in any Python environment. Simply copy and paste the code into a Python file and execute it. The program will guide you through the ordering process and provide you with a receipt of your order.

Enjoy your food from the Variety Food Truck!

(this readme was made with the help of chatgpt)
