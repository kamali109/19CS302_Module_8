# # #Task - Hackerrank Problem

This challenge requires you to print Hello Saveetha! on a single line, and then print the already provided input string to stdout. If you are not familiar with C, you may want to read about the printf() command.

# # Example:

Saveetha

The required output is: Hello, Saveetha! C Programming

EX 36 C program to to print Hello Saveetha! on a single line, and then print the already provided input string to stdout.

## AIM:
To write a C program to print Hello Saveetha! on a single line, and then print the already provided input string to stdout.

## Algorithm
1.Start the program and declare a character array to store the input string.

2.Use gets() or fgets() to read a line of input from the user.

3.Print "Hello Saveetha!" on the first line.

4.Print the user-provided input string on the next line.

5.End the program.

## Program:
/*
C program to find the smallest among three numbers using Structure.
Developed by: KAMALI.S
RegisterNumber:  212222060109
*/
#include <stdio.h>

int main()
{
    char input[100];

    fgets(input, sizeof(input), stdin);

    printf("Hello Saveetha!\n");
    printf("%s", input);

    return 0;
}

## Output:
<img width="444" height="231" alt="image" src="https://github.com/user-attachments/assets/03ee9615-ad8f-4a66-a22c-c00e6ed21fee" />

## Result:
Thus the program was executed and the output was verified successfully.
