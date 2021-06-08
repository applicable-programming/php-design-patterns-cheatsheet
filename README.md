# PHP Design Patterns - Cheatsheet
# MVC (Model-View-Controller)
- Organizes entire project
- Splits thinking process (3 thinking hats?)

### Problem:
All logic is done all over place

### Solution:

Model - Data and business logic

Controller - Flow and data control (?)

View - Presentational logic

# Singleton
- Single instance of object/class for entire project
- Similar to superglobals

### Problem:
ex. databases and files allows single connection per resource 

### Solution:

Singleton always returns same resource

### Example:
Email::sendEmail($email, $message);

Log::error($errorString)
