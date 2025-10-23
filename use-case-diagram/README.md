# Airbnb Clone Backend — Use Case Diagram

This diagram illustrates the interactions between system actors (Guests, Hosts, Admins) and the core backend functionalities of the Airbnb Clone.

![Use Case Diagram](./use_case_diagram.png)

## Key Actors
- **Guest:** Registers, searches, books properties, makes payments, and leaves reviews.
- **Host:** Lists and manages properties, views bookings, and responds to reviews.
- **Admin:** Oversees system management for users, listings, and bookings.
- **Payment Gateway:** Handles secure transaction processing.
- **Email Service:** Sends confirmation and notification messages.

## Relationships
- The “Book Property” use case **includes** “Make Payment”.
- The “Book Property” use case **extends** “Send Confirmation”.
