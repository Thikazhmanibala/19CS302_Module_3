# EX 11 C Program to convert a given binary to decimal value using function without arguments with return type.
## AIM:
To write a C Program to convert a given binary to decimal value using function without arguments with return type.

## Algorithm
1. Read a binary number from the user.
2. Initialize decimal = 0 and base = 1.
3. Use a while loop to extract each digit from right to left.
4. Multiply each digit by its positional value (powers of 2) and add to decimal.
5. Print the decimal result.


## Program:
```
/*
Program to C Program to convert a given binary to decimal value using function without arguments with return type.
Developed by: Thikazhmanibala.K
RegisterNumber: 212222060277
#include <stdio.h>
#include <math.h>

// function prototype
int convert(long long);

int main() {
  long long n;
  scanf("%lld", &n);
  printf("%lld in binary = %d in decimal", n, convert(n));
  return 0;
}

// function definition
int convert(long long n) {
  int dec = 0, i = 0, rem;

  while (n!=0) {
    rem = n % 10;
    n /= 10;
    dec += rem * pow(2, i);
    ++i;
  }

  return dec;
} 
*/
```

## Output:

![image](https://github.com/user-attachments/assets/d4ae27bc-22c9-445c-873a-372e3a311267)


## Result:
Thus the program was executed and the output was verified successfully.
