# EX 20 C program to convert the given string to lowercase without using string functions.
## DATE:
## AIM:
To write a C program to convert the given string to lowercase without using string functions.

## Algorithm
1.Input the string → Read the string s from the user.

2.Iterate through characters → Loop through each character until '\0' (end of string).

3.Check uppercase condition → If s[i] is between 'A' and 'Z', it is an uppercase letter.

4.Convert to lowercase → Add 32 to s[i] to shift it to its lowercase equivalent.

5.Print the result → Display the modified lowercase string. 

## Program:
```
/*
C program to convert the given string to lowercase without using string functions.
Developed by: 
RegisterNumber:  
*/
#include<stdio.h>
int main()
{
    char s[10];
    scanf("%s",s);
    for(int i=0;s[i]!='\0';i++)
    {
        if((s[i]>='A')&&(s[i]<='Z'))
        s[i]=s[i]+32;
    }
    printf("Lower case String is:%s",s);
}
```

## Output:
![image](https://github.com/user-attachments/assets/dbe40747-fecb-4c3b-903c-45afb5945b0d)



## Result:
Thus the program was executed and the output was verified successfully.
