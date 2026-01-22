Code Structure
🔹 Product Class
The Product class stores product details such as product ID, name, and price. Each object represents a single supermarket item.

🔹 SupermarketBillingSystem Class
This is the main class that controls the system.

Data Storage
products (dictionary): Stores available products using product ID as the key
cart (dictionary): Stores selected products with quantity and price

Functional Explanation
🔸 add_products()
Preloads the system with predefined products to keep the program simple and user-friendly.

🔸 view_products()
Displays all available products along with their ID, name, and price.

🔸 add_to_cart()
Allows users to select a product by ID and specify quantity. If the product already exists in the cart, its quantity is updated.

🔸 generate_bill()
Calculates the total cost of all items in the cart and displays a formatted bill.

🔸 menu()
Provides a menu-driven interface that lets users perform operations until they choose to exit.

Concepts Used
Python
Object-Oriented Programming (OOP)
Dictionaries
Loops and conditionals
Menu-driven programming

