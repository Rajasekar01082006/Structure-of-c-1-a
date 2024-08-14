# Structure-of-c-1-
/*
★ file: sum.c
★ author: [Your Name]
* description: Program to find the sum of a given number and a predefined constant.
*/

// Include the necessary library
#include <stdio.h>

// Define a constant
#define x 20

// Global declaration of the sum function
int sum(int y);

// Main function
int main(void) {
    int y = 55;
    printf("Sum: %d\n", sum(y));
    return 0;
}

// Definition of the sum function
int sum(int y) {
    return y + x;
}
