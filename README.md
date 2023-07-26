ALX Printf Project

Welcome to the ALX Printf Project! This is a custom implementation of the printf function in the C programming language. The printf function is commonly used to display formatted output to the standard output stream in C programs. In this project, we have created our version of this function, named _printf, which follows similar behavior and functionality as the standard printf.

Project Objectives

The main goal of this project is to create a function that takes a format string and other optional arguments, and then prints the formatted output to the console. The format string acts as a set of instructions, guiding the function on how to display the data provided in the arguments. The format string can contain plain text and format specifiers, which begin with the percent sign (%), followed by a letter (e.g., %c, %s, %d, etc.).

What it includes
Our _printf function supports the following conversion specifiers and their individual interlocking attributes:

%c: Prints a single character.
%s: Prints a string of characters.
%%: Prints a single percent sign.

Apart from the above conversion specifiers, we have kept this implementation relatively simple, and we do not handle field width, precision, flag characters, or length modifiers as found in the standard printf function of the C library. This decision has been made to focus on the core functionality and to make the project more approachable for learners.

AUTHORS
Destiny Matuse
Prince Chibueze Isaac
