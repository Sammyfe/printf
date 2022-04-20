Title:
_printf
The _printf function is a custom implementation of the C programming function printf. It returns the number of characters printed and writes the output to stdout. It includes the conversion specifiers : c, s, %, d, x, X, u, o, rot13 and i.

Description:
The described _printf function produces an output format based on the identifiers that are listed below. When the function is successful, it returns the length of the string passed, and returns (-1) when the function fails.

Format identifiers:
%c: Prints a character
%s: Prints a string
%d: Prints integers
%i: Prints integers
%b: Prints the binary representation of the unsigned decimal
%u: Prints integers that are unsigned
%x: Prints lowercase hexadecimal
%X: Prints uppercase hexadecimal
%r: Prints a reversed string
%R: Prints the passed string in Rot13.

Usage:
All the files are to be compiled on Ubuntu 14.04 LTS
Compile your code with gcc -Wall -Werror -Wextra -pedantic *.c
Include the main.h header file on the functions using the _printf

Example:
#include main.h
_printf(The %s ran %d times! -%c boy, 10, 'C');

return 0;

Output:
The boy ran 10 times! -C

Project by:
sammyfe 
