LKT (Let's Keep Traveling) - Command Line Flight Management System
LKT is a command-line interface (CLI) flight management system that enables users to search, book, and manage flights efficiently. Developed as part of an advanced programming project, it implements object-oriented principles and interacts with a flight database via a series of commands, making it easy for users to manage their travel plans.

Key Features
1) Flight Management:
Search for flights by origin, destination, and date.
Filter flights by price, airline, and class.
Get detailed information on flights, including available seats and cost.

2) Booking System:
Book tickets based on flight details.
Choose from different flight classes (economy, business) and types (refundable, non-refundable).
Manage bookings, including adding and removing tickets.

3) Flight Reporting:
Generate detailed reports such as the most popular destinations and top airlines.
Retrieve statistics like average flight costs and minimum/maximum prices.

4) Connecting Flights:
Search for connecting flights between cities and calculate total travel cost and duration.

6) User-Friendly CLI:
Built as a command-line tool with intuitive commands like GET, POST, and DELETE.
Supports error handling with appropriate messages like Not Found, Bad Request, and Permission Denied.


Files in the Repository:
main.py: The main entry point for running the CLI program.
agency.py: Manages core flight and booking operations.
handler.py: Handles various commands and user input.
modules.py: Contains helper functions and classes used throughout the project.
