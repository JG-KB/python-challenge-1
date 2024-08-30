# Mo's Food Truck Menu Ordering System

Welcome to Mo's Food Truck Menu Ordering System! This Python-based application allows customers to order food items from a menu categorized into Snacks, Meals, Drinks, and Desserts. The system calculates the total cost and nutritional information for the order, ensuring an accurate and enjoyable ordering experience.

## Features

- **Menu Categories**: The menu is divided into Snacks, Meals, Drinks, and Desserts, each with various items.
- **Nested Menu Structure**: Some menu items have sub-items (e.g., different types of pizza or burgers).
- **Nutritional Information**: Each menu item includes detailed nutritional information (calories, carbs, fats, and protein).
- **Continuous Ordering**: Customers can keep adding items to their order until they decide to complete it.
- **Order Summary**: The system provides a detailed summary of the items ordered, including total cost and nutritional breakdown.
- **Discount for No Orders**: If no items are ordered, the system provides a discount code for future visits.

## Usage

### Ordering Process

1. **Select a Menu Category**: Choose from Snacks, Meals, Drinks, or Desserts by typing the corresponding number.
2. **Choose a Menu Item**: After selecting a category, you'll be prompted to choose an item from that category.
3. **Specify Quantity**: Input the quantity of the selected item you'd like to order.
4. **Continue Ordering or Complete Order**: You can continue adding items to your order or complete the order when you're done.

### Order Summary

Once you decide to complete your order, the system will display a summary including:

- **Itemized List**: A list of all items ordered, including quantity and price.
- **Total Cost**: The total cost of the order.
- **Nutritional Breakdown**: Total calories, carbs, fats, and protein for the entire order, along with percentages of calories from each macronutrient.

### Special Features

- **Nutritional Information**: Detailed nutritional info is provided for each item, helping customers make informed choices.
- **Order Update**: If you order an item more than once, the system updates the quantity instead of adding a duplicate.
- **Exit Without Ordering**: If no items are ordered, the system asks for confirmation before exiting and provides a discount code for future visits.

## Code Structure

- **Menu Dictionary**: Contains the menu items, prices, and nutritional information organized by category.
- **Order List**: A list that stores each ordered item, its price, quantity, and nutritional information.
- **Main Loop**: Continuously runs the ordering process until the customer decides to stop.
- **Order Summary Calculation**: Totals the cost and nutritional information for all ordered items and displays the results.

## Future Enhancements

Some potential future enhancements for the system include:

- **Advanced User Interface**: Implementing a graphical user interface (GUI) for a more user-friendly experience.
- **Payment Integration**: Adding functionality to process payments directly within the system.
- **Customization Options**: Allowing customers to customize their orders, such as choosing toppings for pizzas or add-ons for burgers.

## Requirements

- **Python 3.10.14**: Ensure that you have Python installed on your machine.

---

We hope you enjoy using Mo's Food Truck Menu Ordering System. Great food made with love is on the way!
