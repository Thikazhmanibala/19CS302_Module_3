# EX 12 C program to check whether the given number is prime or not using function without return type and with arguments.
## AIM:
To write a C program to check whether the given number is prime or not using function without return type and with arguments.

## Algorithm
1. Set the number (87 in this case).
2. Initialize a flag (isPrime) to true.
3. Loop from 2 to number/2 and check if any number divides it evenly.
4. If any divisor is found, set isPrime to false.
5. Print whether the number is prime based on the flag.


## Program:
```
/*
C program to check whether the given number is prime or not using function without return type and with arguments.
Developed by: Thikazhmanibala.K
RegisterNumber: 212222060277
#include<stdio.h>
int main()
{
    int i,n=87;
    for(i=2;i<=n;i++)
    if(n%i==0)
    {
    printf("%d is a prime number.",n);
    break;
    }
    else
    {
    printf("%d is not a prime number.",n);
    break;
    }
    return 0;
} 
*/
```

## Output:

![image](https://github.com/user-attachments/assets/f3c43cb6-0ff8-4b0b-8631-c18d47eb5d09)


## Result:
Thus the program was executed and the output was verified successfully.
