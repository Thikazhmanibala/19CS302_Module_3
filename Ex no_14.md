# EX 14 C program to delete first element in an array.
## AIM:
To write a C program to delete first element in an array.

## Algorithm
1. Read the size of the array and its elements.
2. Read the position of the element to be deleted.
3. Check if the position is valid.
4. Shift elements from that position to the left by one place.
5. Print the updated array after deletion.
  

## Program:
```
/*
Program to delete first element in an array.
Developed by: Mariam Sherin
RegisterNumber: 212222060143
#include <stdio.h>

int main() {
    int arr[100], n, pos, i;

    printf("Enter number of elements: ");
    scanf("%d", &n);

    printf("Enter %d elements:\n", n);
    for(i = 0; i < n; i++)
        scanf("%d", &arr[i]);

    printf("Enter the position to delete (0 to %d): ", n - 1);
    scanf("%d", &pos);

    if(pos < 0 || pos >= n) {
        printf("Invalid position!\n");
    } else {
        for(i = pos; i < n - 1; i++) {
            arr[i] = arr[i + 1];
        }
        n--;

        printf("Array after deletion:\n");
        for(i = 0; i < n; i++)
            printf("%d ", arr[i]);
        printf("\n");
    }

    return 0;
}

*/
```

## Output:

![image](https://github.com/user-attachments/assets/62f1f80e-9640-4862-9e7b-60075b43b3b0)


## Result:
Thus the program was executed and the output was verified successfully.
