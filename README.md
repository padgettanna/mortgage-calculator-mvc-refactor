# Mortgage Calculator – ASP.NET Core MVC Refactor

This repository contains an early web-based version of a Mortgage Calculator application refactored from a console-based C# program into an ASP.NET Core MVC application.

This snapshot represents the **software design and engineering enhancement** stage of the project and focuses on architecture, separation of concerns, and maintainability rather than persistence or authentication.

## Project Context

The Mortgage Calculator was originally developed as a console application during the Microsoft Software and Systems Academy (MSSA).  
As part of a Computer Science capstone, the application was refactored into a web application to better align with modern software engineering practices.

This repository captures the application **before database integration** and user authentication were added.

A more complete version of the application, including database persistence and user-specific calculation history, is available in the main project repository.

## Focus of This Version

This version of the application demonstrates:

- Refactoring legacy-style code into an ASP.NET Core MVC architecture
- Separation of concerns between controllers, domain logic, and views
- Encapsulation of mortgage calculation logic in a domain layer
- Model-level input validation
- Clean, maintainable project structure aligned with industry practices

## Features

- Mortgage payment calculation
- Loan eligibility evaluation based on payment-to-income ratio
- Support for multiple loan terms and payment schedules
- User-friendly web interface for data entry and results display

## Technology Stack

- ASP.NET Core MVC
- C#
- .NET 10
- Razor Views
- Bootstrap (basic styling)

## Notes

This repository is intentionally limited in scope to highlight architectural and design improvements.
Database persistence, authentication, and historical calculation tracking are implemented in later versions of the application.

## Author

Anna Padgett
