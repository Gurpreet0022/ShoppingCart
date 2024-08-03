Online Shopping Cart System
==========================


A simple online shopping cart system implemented in Python.

Features
--------

* Add products to the cart with their prices and quantities
* Remove products from the cart
* Update the quantity of a product in the cart
* Calculate the total cost of the products in the cart
* Display the products in the cart along with their prices and quantities

Classes
-------

### Product

* `__init__(self, name, price, quantity)`: Initializes a product with a name, price, and quantity
* Attributes:
	+ `name`: The name of the product
	+ `price`: The price of the product
	+ `quantity`: The quantity of the product

### ShoppingCart

* `__init__(self)`: Initializes an empty shopping cart
* Methods:
	+ `add_product(self, product)`: Adds a product to the cart and updates the total cost
	+ `remove_product(self, product_name)`: Removes a product from the cart and updates the total cost
	+ `update_quantity(self, product_name, new_quantity)`: Updates the quantity of a product in the cart and updates the total cost
	+ `calculate_total_cost(self)`: Calculates the total cost of the products in the cart
	+ `display_cart(self)`: Displays the products in the cart along with their prices and quantities

Example Usage
-------------
cart = ShoppingCart()

product1 = Product("Apple iPhone", 999.99, 1) product2 = Product("Samsung TV", 1299.99, 2)

cart.add_product(product1) cart.add_product(product2)

cart.display_cart()

cart.update_quantity("Apple iPhone", 2)

cart.display_cart()

cart.remove_product("Samsung TV")

cart.display_cart()



Contributing
------------

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

Author
-------

Gurpreet Kaur
