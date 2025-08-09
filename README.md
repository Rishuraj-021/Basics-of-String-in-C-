# Basics-of-String-in-C-

## Aim:
To study and implement basic string operations in C++ such as:

## Theory:
A string in C++ is a sequence of characters stored in contiguous memory locations and terminated by a null character '\0' when using C-style strings, or managed dynamically when using the std::string class from the C++ Standard Library.

Common operations include:

Input and Output of Strings – Can be done using cin, getline(), and cout.

Concatenation – Joining two strings together using the + operator or append() function.

Reversal – Changing the order of characters so the last character becomes first.

Traversal – Accessing each character in the string using loops.

Advantages of std::string over C-style strings:

Automatic memory management

Built-in functions for manipulation

Easier concatenation and comparison

## Algorithm:
### Algorithm:(A) Print a String (already stored)

Start

Declare and initialize a string variable with some text.

Use cout to display the string.

End.

### (B) Take String as Input and Display It
Algorithm:

Start

Declare a string variable.

Use getline(cin, variable_name) to take input (supports spaces).

Use cout to display the entered string.

End.

### (C) Concatenation of Two Strings
Algorithm:

Start

Declare two string variables.

Take input for both strings using getline().

Create a third string as the sum of the first and second strings using + or append().

Display the concatenated string.

End.

### (D) Reverse a String
Algorithm:

Start

Declare a string variable.

Take input for the string using getline().

Use a loop to swap characters from start and end towards the middle OR use built-in reverse() function.

Display the reversed string.

End.



## Conclusin:
By performing the above operations, we have learned how to handle strings in C++ effectively. We practiced input, output, concatenation, and reversal, which are fundamental operations for string manipulation. Using the std::string class simplifies these operations compared to C-style strings, making programs easier to write and maintain.
