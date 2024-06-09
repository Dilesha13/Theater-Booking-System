Introduction:

This project revolves around a Java-based application designed to manage ticket bookings for a theater. It provides functionalities to facilitate ticket purchases, seat allocation, cancellation, and more.

Key Components:

  1)Person Class:

      *The Person class represents individuals purchasing tickets.
      *It stores essential details like name, surname, and email.
      
  2)Ticket Class:

      *The Ticket class encapsulates information about a purchased ticket.
      *It includes data such as row number, seat number, price, and the person associated with         the ticket.
      
  3)Theatre Class:

      *The central component of the application, the Theatre class, orchestrates the theater's         operations.
      *It offers various functionalities through a menu-driven interface:
      
                  # Buying tickets
                  # Printing the seating area
                  # Canceling tickets
                  # Listing available seats
                  # Saving ticket information to a file
                  # Loading ticket information from a file
                  # Printing ticket information and total price
                  # Sorting tickets by price
Workflow:

The application follows a user-friendly workflow:

  1) Users interact with the system through a menu interface.
     
  2)Based on the chosen option, users can perform actions like purchasing tickets or viewing        available seats.
  
  3)The application validates user inputs to ensure correctness and provides appropriate            feedback.

Notable Features:

  1)Input Validation: The application validates user inputs to prevent errors and ensure data       integrity.
  
  2)Persistence: Ticket information can be saved to a file, allowing users to resume sessions       later.
  
  3)Sorting: The system can sort tickets by price, enabling users to view ticket information        efficiently.
