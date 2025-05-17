# EX 19 C program to perform basic left and right shift operations on a given integer and display the result.
## DATE:
## AIM:
To write a C program to perform basic left and right shift operations on a given integer and display the result.

## Algorithm
1.Input the number → Read an integer num from the user.

2.Perform left shift → Compute num << 2, which shifts bits left by 2 positions 

3.Perform right shift → Compute num >> 2, which shifts bits right by 2 positions

4.Print results → Display the values after left and right shift operations.

5.End program → Return 0 to indicate successful execution  

## Program:
```
/*
C program to perform basic left and right shift operations on a given integer and display the result.
Developed by: 
RegisterNumber:  
*/
#include <stdio.h>
int main() {
    int num;
    scanf("%d",&num);
    printf("After Left Shift Operation value of a is:%d\n", num << 2);
    printf("After Right Shift Operation value of a is:%d\n", num >> 2);
    return 0;
}

```

## Output:
![image](https://github.com/user-attachments/assets/11996ec6-3e7b-4a98-a097-78839644f212)



## Result:
Thus the program was executed and the output was verified successfully.
