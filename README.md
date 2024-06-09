Introduction:

This project revolves around a Java-based application designed to manage ticket bookings for a theater. It provides functionalities to facilitate ticket purchases, seat allocation, cancellation, and more.

Key Components:

Person Class:

The Person class represents individuals purchasing tickets.
It stores essential details like name, surname, and email.
Ticket Class:

The Ticket class encapsulates information about a purchased ticket.
It includes data such as row number, seat number, price, and the person associated with the ticket.
Theatre Class:

The central component of the application, the Theatre class, orchestrates the theater's operations.
It offers various functionalities through a menu-driven interface:
Buying tickets
Printing the seating area
Canceling tickets
Listing available seats
Saving ticket information to a file
Loading ticket information from a file
Printing ticket information and total price
Sorting tickets by price
Workflow:

The application follows a user-friendly workflow:

Users interact with the system through a menu interface.
Based on the chosen option, users can perform actions like purchasing tickets or viewing available seats.
The application validates user inputs to ensure correctness and provides appropriate feedback.
Notable Features:

Input Validation: The application validates user inputs to prevent errors and ensure data integrity.
Persistence: Ticket information can be saved to a file, allowing users to resume sessions later.
Sorting: The system can sort tickets by price, enabling users to view ticket information efficiently.
