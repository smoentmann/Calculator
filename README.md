# Calculator Application

A simple Java console-based calculator that performs basic arithmetic operations:

* Addition
* Subtraction
* Multiplication
* Division

## Features

* Accepts user input using `Scanner`
* Supports decimal numbers (`double`)
* Handles division by zero errors
* Displays an error message for invalid menu choices

## Technologies Used

* Java
* Java `Scanner` class for input handling

## Project Structure

```plaintext
day3/
└── Calculator.java
```

## How It Works

1. The program asks the user to enter two numbers.
2. A menu of operations is displayed.
3. The user selects an operation by entering a number:

   * `1` → Addition
   * `2` → Subtraction
   * `3` → Multiplication
   * `4` → Division
4. The result is displayed in the console.

## Example Run

```plaintext
Enter the first number
10

Enter the second number
5

Choose an operation
1. Addition
2. Subtraction
3. Multiplcation
4. Division

1

Result:15.0
```

## How to Compile and Run

### Compile

```bash
javac day3/Calculator.java
```

### Run

```bash
java day3.Calculator
```

## Error Handling

### Division by Zero

If the user attempts to divide by zero, the program displays:

```plaintext
Error: Division by zero is not allowed
```

### Invalid Menu Choice

If the user enters a number outside the available options, the program displays:

```plaintext
Invalid choice
```

## Possible Improvements

* Add support for more operations (modulus, exponentiation, square root)
* Use a `switch` statement instead of multiple `if-else` conditions
* Add input validation for non-numeric entries
* Allow repeated calculations without restarting the program
* Close the `Scanner` object to prevent resource leaks

## Author

Created as a beginner Java practice project.

