# C-PROGRAMMING
A PROGRAM TO FIND THE GIVEN CHARACTER IS ALPHABET OR NOT.
#include <stdio.h>

int main() {
    char a;
    int res;
    printf("Enter a CHARACTER: ");
    scanf(" %c", &a);
    res = (a >= 'A' && a <= 'Z') || (a >= 'a' && a <= 'z');
    printf("The %c is an ALPHABET: %d\n", a, res);
    return 0;
}

