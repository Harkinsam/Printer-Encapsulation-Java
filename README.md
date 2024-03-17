# Printer Simulation

This Java project simulates a computer printer and demonstrates proper encapsulation techniques.

## Description

The `Printer` class represents a real computer printer with fields for toner level, number of pages printed, and whether it's a duplex printer (capable of printing on both sides of the paper). It includes methods to fill up the toner and simulate printing a page.

## Features

- **Toner Level Control:** Keep track of the toner level and prevent overfilling.
- **Page Count Management:** Track the number of pages printed accurately.
- **Duplex Printing Support:** Simulate duplex printing capabilities.

## Usage

1. Create an instance of the `Printer` class:
   ```java
   Printer printer = new Printer(50, false);
Use the following methods to interact with the printer:

1. `int printPages(int pages)`: Simulates printing a specified number of pages and returns the actual number of pages printed.

2. `void fillToner(int amount)`: Fills up the toner by the specified amount (up to a maximum of 100%).
# Printer Class Structure

## Fields

- `tonerLevel`: Current level of toner (0 to 100%).
- `pagesPrinted`: Number of pages printed so far.
- `duplexPrinter`: Flag indicating whether it's a duplex printer.

## Methods

- `int printPages(int pages)`: Simulates printing a specified number of pages and returns the actual number of pages printed.
    - Parameters:
        - `pages`: Specifies the number of pages to print.

- `void fillToner(int amount)`: Fills up the toner by the specified amount (up to a maximum of 100%).
    - Parameters:
        - `amount`: Specifies the amount to fill the toner (percentage).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
