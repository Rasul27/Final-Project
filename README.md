https://www.canva.com/design/DAGFeMoDJ3U/6TIFAezF9mUAKyTKnwuN6A/edit?utm_content=DAGFeMoDJ3U&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

# Project Title: Order Management System
## Description:

The Order Management System is a simple command-line application designed to manage orders for a business.
It allows users to add new orders, update order status and tracking numbers, delete orders, display all orders, and save the orders to a file for future reference.


## Objectives:
- Create a user-friendly interface for managing orders.
- Allow users to add new orders with customer details, product information, status, and tracking numbers.
- Enable users to update the status and tracking number of existing orders.
- Provide functionality to delete orders if necessary.
- Implement a feature to display all orders in a formatted manner.
- Enable users to save the orders to a file for record-keeping purposes.

## Project Requirement List:
 - User-friendly command-line interface.
 - Add order functionality with customer name, product name, status, and tracking number fields.
 -  Update order status functionality by index.
 -  Update order tracking number functionality by index.
 -  Delete order functionality by index.
 -  Display all orders with index, customer name, product name, status, and tracking number columns.
 - Save orders to a file.
 -  Load orders from a file.
 -  Proper input validation to handle invalid user input.
 -  Use of appropriate data structures such as vectors to store orders.
## Documentation:
## Purpose
- The project aims to simplify order management by providing functionalities to add, update, delete, display, and save orders.
## Data Structures
- Order Struct: Holds customer name, product name, status, and tracking number.
- OrderTracker Struct: Manages a vector of Order objects and provides functions to manipulate them.
## Functions
addOrder(const Order& order): Adds a new order.
updateStatus(int index, const string& newStatus): Updates the status of an order by index.
updateTrackingNumber(int index, const string& newTrackingNumber): Updates the tracking number of an order by index.
deleteOrder(int index): Deletes an order by index.
displayOrders(): Displays all orders.
saveToFile(const string& filename): Saves orders to a file.
loadFromFile(const string& filename): Loads orders from a file.
## Usage
Compile the code using a C++ compiler.
Run the executable.
Follow the menu prompts to add, update, delete, display orders, or save and exit.
Save changes using "Save and Exit" before exiting.
## Example


Menu:
1. Add Order
2. Update Status
3. Update Tracking Number
4. Delete Order
5. Display Orders
6. Save and Exit
Enter your choice: 1
Enter customer name: John Doe
Enter product name: Widget
Enter status: Processing
Enter tracking number: 12345

Menu:
1. Add Order
2. Update Status
3. Update Tracking Number
4. Delete Order
5. Display Orders
6. Save and Exit
Enter your choice: 5
Index   Customer Name   Product Name    Status       Tracking Number
0       John Doe        Widget          Processing   12345
 
How to Use:
Compile the source code using a C++ compiler.
Run the compiled executable file.
Follow the on-screen menu prompts to perform desired actions such as adding, updating, deleting, or displaying orders.
Ensure to save changes using the "Save and Exit" option before exiting the application
