# EX 16 C program to find minimum between three fraction numbers using conditional operator.
## DATE:
## AIM:
To write a C program to find minimum between three fraction numbers using conditional operator.

## Algorithm
1.Input three numbers → Read a, b, and c from the user.

2.Compare a and b → If a < b, proceed to compare a with c.

3.Determine minimum if a < b → If a < c, set min = a, otherwise min = c.

4.Determine minimum if b ≤ a → If b < c, set min = b, otherwise min = c.

5.Print the result → Display the minimum value among a, b, and c. 

## Program:
```
/*
C program to find minimum between three fraction numbers using conditional operator.
Developed by:santhiya c 
RegisterNumber:212223060247  
*/

#include <stdio.h>
int main()
{
    float a,b,c,min;
    scanf("%f %f %f",&a,&b,&c);
    if(a<b)
    min=a<c?a:c;
    else
    min=b<c?b:c;
    printf("Minimum between %.3f, %.3f and %.3f = %.3f",a,b,c,min);
}
```

## Output:
![image](https://github.com/user-attachments/assets/6efb2a1f-64ca-4295-9054-bf131ab4aac4)



## Result:
Thus the program was executed and the output was verified successfully.
