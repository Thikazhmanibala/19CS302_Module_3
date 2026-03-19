# EX 15 C program to read n elements as input and check whether the first element is divisible by 3
## AIM:
To write a C program to read n elements as input and check whether the first element is divisible by 3

## Algorithm
1. Read the number of elements and store them in an array.
2. Check if the array has at least one element.
3. Read all the array elements from the user.
4. Check if the first element is divisible by 3 using modulus.
5. Print whether it is divisible by 3 or not.
  

## Program:
```
/*
Program to read n elements as input and check whether the first element is divisible by 3
Developed by: Thikazhmanibala.K
RegisterNumber: 212222060277
#include <stdio.h>
 
int main()
{
    int a[1000],i,n;  
 
    scanf("%d\n",&n);
 
    for(i=0;i<n;i++)
    {
        scanf("%d ", &a[i]);
    }
 
    if(a[0]%3!=0)
    {
        printf("The first element %d is not divisible by 3", a[0]);
    }
    else
    {
        printf("The last element %d is divisible by 3", a[n-1]);
    }
 
    return 0;
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/e4391792-9875-4636-9add-6aa180f7473c)


## Result:
Thus the program was executed and the output was verified successfully.
