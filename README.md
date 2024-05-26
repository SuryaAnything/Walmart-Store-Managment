# Walmart Store Management System

## Overview

The Walmart Store Management System is a command-line application designed to efficiently manage inventory and streamline store operations. It provides various functionalities to add, update, delete items, manage aisles, generate alerts, bill customers, and perform other tasks related to inventory management.

## Features

- **Inventory Management**: Add, update, and delete items in the inventory.
- **Aisle Management**: Manage aisles by adding or deleting them.
- **Availability Check**: Check availability of items based on quantity and expiry date.
- **Alert Generation**: Generate alerts for threshold quantities, ready-to-eat items nearing expiry, and dairy products expiring soon.
- **Aisle Optimization**: Merge aisles to optimize inventory organization.
- **Billing**: Bill customers for their purchases.
- **Purchase Analysis**: Display items more often bought with a particular item.
- **Search Functionality**: Perform range searches on items.
- **Data Persistence**: Write updated product lists to the database for future reference.

## Usage

1. **Running the Application**: Compile and run the main C file to start the application.
2. **Menu Navigation**: Follow the on-screen instructions to navigate through the menu and perform various operations.
3. **Input Handling**: Enter the corresponding option number to execute the desired functionality.

## Data Files

- **items.json**: JSON file containing item information, including ID, name, quantity, expiry date, and threshold.
- **customers.json**: JSON file containing customer information, including name and purchased items.

## Dependencies

- **Programming Language**: C
- **Libraries**: Standard C libraries
- **Data Format**: JSON (for input/output of item and customer data)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
