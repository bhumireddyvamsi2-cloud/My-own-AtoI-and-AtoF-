# My-own-AtoI-and-AtoF-
The program reads a number from the command line, scans it for a decimal point, and routes it to custom integer or float parsing functions. Inside, it uses loops, ASCII character math, and sign detection to convert strings into numeric values, demonstrating pointers, string traversal, and manual type conversion without standard functions.
# Custom atoi() and atof() Implementation in C

## Description

This project implements custom versions of the standard C library functions `atoi()` and `atof()` without using the built-in conversion functions.

The program takes a numeric value through the command line and automatically determines whether the input is an integer or a floating-point number.

## Features

* Converts string to integer using `my_atoi()`.
* Converts string to floating-point number using `my_atof()`.
* Supports positive and negative numbers.
* Supports decimal values.
* Stops conversion when a non-numeric character is encountered.
* Uses command-line arguments for input.
* Does not use built-in `atoi()` or `atof()` functions.

## Technologies Used

* C Programming
* GCC Compiler
* Command Line Arguments

## Functions

### `my_atoi()`

Converts a numeric string into an integer.

Example:

```text
Input: 12345
Output: 12345
```

```text
Input: -123
Output: -123
```

### `my_atof()`

Converts a numeric string containing a decimal point into a floating-point value.

Example:

```text
Input: 123.45
Output: 123.450000
```

```text
Input: -45.67
Output: -45.670000
```

## Compilation

Compile the program using:

```bash
gcc program.c
```

## Execution

Run the program using:

```bash
./a.out 123
```

Output:

```text
123
```

For a floating-point value:

```bash
./a.out 123.45
```

Output:

```text
123.450000
```

## Sample Test Cases

| Input     | Output       |
| --------- | ------------ |
| `123`     | `123`        |
| `-123`    | `-123`       |
| `0`       | `0`          |
| `123.45`  | `123.450000` |
| `-45.67`  | `-45.670000` |
| `12.5abc` | `12.500000`  |

## Project Structure

```text
Custom-atoi-atof/
│
├── program.c
└── README.md
```

## Concepts Used

* Functions
* Strings
* Arrays
* Pointers
* Loops
* Conditional statements
* Command-line arguments
* String-to-number conversion

## Author

BHUMIREDDY MOHANA SAI VAMSIDHAR REDDY

## License

This project is created for educational and practice purposes.

