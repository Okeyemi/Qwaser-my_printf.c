# Qwaser-my_printf.c


## Usage
The usage of this my_printf is to implement custom printf-like function in C language. 
The function, my_printf, accepts a string "format" and a variable number of arguments, 
and outputs the text to the console using write() function from unistd.h library.
The function supports following format specifiers: %s for string, %d for signed integer,
%c for character, %u for unsigned integer, %o for octal, %x for hexadecimal, and %p for pointer address