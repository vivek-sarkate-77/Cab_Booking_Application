# Cab_Booking_Application
1.Purpose:
Developed a web-based Cab Booking System to allow users to book cabs, manage drivers, and view trip history.

2.Architecture:
Implemented using layered architecture with Controller, Service, and Repository layers in Spring Boot.

3.User Roles:
Admin: Manage drivers, view all bookings
Customer/User: Register, login, book a cab, view booking history

4. Modules Covered:
User Module: Registration, login, profile management
Cab Module: Add, update, view, delete cab details
Booking Module: Book cab, view trip history, cancel trip
Driver Module: Assign drivers, update driver status
Payment Module (optional): Basic fare calculation and payment simulation

5.Database Design (MySQL):
Tables: User, Driver, Cab, Booking, TripHistory, Payment
Used foreign key relationships to maintain data integrity

6.Spring Boot Features Used:
REST APIs using @RestController
Dependency Injection with @Autowired
CRUD operations using JpaRepository
Exception handling with @ControllerAdvice
Validation using @Valid and @NotNull
