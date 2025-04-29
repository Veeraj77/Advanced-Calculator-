# Advanced Calculator

A Java-based console application that performs basic arithmetic operations, including addition, subtraction, multiplication, and division.

---

## Features

- **Addition**: Adds two numbers.
- **Subtraction**: Subtracts the second number from the first.
- **Multiplication**: Multiplies two numbers.
- **Division**: Divides the first number by the second (handles division by zero).

---

## Prerequisites

- Java Development Kit (JDK) 8 or higher.


## Functions Used

### Main.java
public static void main(String[] args)

Entry point of the application. Displays the menu and takes user input for performing calculations.

###Calculator.java

public double add(double a, double b)

Adds two numbers and returns the result.

public double subtract(double a, double b)

Subtracts the second number from the first and returns the result.

public double multiply(double a, double b)

Multiplies two numbers and returns the result.

public double divide(double a, double b)

Divides the first number by the second and returns the result. If division by zero is attempted, it throws an exception.

### Input.java

public static double getInput()

Prompts the user to input a number and returns it as a double. Ensures that the input is valid.

### InvalidInputException.java
public InvalidInputException(String message)

Custom exception class to handle invalid input errors such as non-numeric values or division by zero.


