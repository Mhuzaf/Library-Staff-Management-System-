# Staff Management System

A C#/.NET staff management system developed as an academic software engineering project, combining database integration, input validation, and automated testing.

## Overview

The system manages staff records containing information such as:

- Staff ID
- Name
- Role
- Email
- Hire Date
- Active Status

The project uses a database-backed architecture to retrieve staff records through SQL stored procedures and a dedicated data connection layer. A validation layer ensures that staff information meets defined business rules before being accepted.

## Key Features

- Staff record management
- Database integration using SQL
- Stored-procedure-based staff retrieval
- Input validation and error handling
- Boundary-value validation for staff fields
- Email format validation
- Hire-date validation
- Automated unit testing with MSTest
- Test-Driven Development (TDD) practices
- Positive and negative test cases
- Comprehensive test plans and test logs

## Testing

The project includes automated tests covering:

- Class and property functionality
- Database record retrieval
- Minimum and maximum field boundaries
- Invalid and valid email formats
- Name validation
- Role validation
- Valid and invalid hire dates
- Additional edge cases and negative scenarios

## Technologies

- **C#**
- **.NET**
- **SQL**
- **MSTest**
- **Visual Studio**
- **SQL Stored Procedures**
- **Test-Driven Development (TDD)**
