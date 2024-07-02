# Hatirjheel Bus Ticket Booth System
This Java project simulates a bus ticket booking system where users can purchase tickets for different routes and stations. It includes custom exceptions for handling insufficient balance during ticket purchase.

## Features
- Manage bus stations with unique codes.
- Calculate ticket prices based on distance between stations.
- Handle balance exceptions if the customer has insufficient funds.
- Generate ticket slips with detailed information.

## Project Structure
- **BalanceException:** Custom exception class thrown when a user attempts to purchase a ticket without sufficient balance.
- **BusStation:** Represents a bus station with a name and code.
- **Person:** Models a person with money and ticket price attributes, with methods to check balance before ticket purchase.
- **StationCode:** Interface defining constants for station codes used across the application.
- **TicketBooth:** Main class that models a ticket booth, allowing users to purchase tickets based on routes and stations.
- **TestBooth:** Contains the `main` method for testing and demonstrating the functionality of the `TicketBooth` class.

## Example Output
![hatirjheel bus station](https://github.com/esikaupoma/hatirjheel-bus-ticket-booth-system/assets/126023004/90f5c06f-757f-4b1a-ace7-2fdf3d627d99)

