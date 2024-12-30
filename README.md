# Python Programming Lab Projects

This repository contains a collection of Python programs developed during college practical labs. The projects demonstrate various programming concepts including unit testing, OOP, and practical applications.

## Project Files

### 1. Calculator Module (`calculator.py`)

A utility module that provides basic arithmetic operations:

- Addition of two numbers
- Subtraction of two numbers
- Multiplication of two numbers
- Division of two numbers (with zero division handling)
- Finding maximum of three numbers
- Well-documented functions with docstrings

### 2. Calculator Tests (`test_calculator.py`)

Unit tests for the calculator module:

- Tests for all arithmetic operations
- Edge case testing (zero, negative numbers)
- Division by zero error testing
- Multiple test cases for each operation
- Uses Python's unittest framework

### 3. OTP Generator (`generateOTP.py`)

Email-based OTP verification system:

- Generates random 6-digit OTP
- Sends OTP via email using SMTP protocol
- Validates user input against generated OTP
- Features:
  - Email authentication
  - SMTP server configuration
  - User input validation
  - Secure OTP generation

### 4. Grade Management System (`Grade.py`)

Object-oriented implementation of a student grading system:

- Student class with following methods:
  - Add grades (with validation for 0-100 range)
  - Calculate average grade
  - Find highest grade
  - Find lowest grade
- Error handling for empty grade lists
- Data validation for grade inputs

### 5. Grade System Tests (`test_Grade.py`)

Comprehensive unit tests for the Grade Management System:

- Tests for valid and invalid grade additions
- Average grade calculation tests
- Highest and lowest grade tests
- Empty grade list handling
- Edge case testing

## Getting Started

### Prerequisites

- Python 3.x
- SMTP server access (for OTP functionality)
- unittest module (included in Python standard library)

### Installation

1. Clone this repository:
