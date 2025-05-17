# EX 17 C Program to compare two strings without using strcmp().
## DATE:
## AIM:
To write a C Program to compare two strings without using strcmp().

## Algorithm
1.Input two strings → Read str1 and str2 from the user.

2.Initialize variables → Set flag = 0 and i = 0 for iteration.

3.Iterate through characters → Loop through both strings until a null character ('\0') is encountered.

4.Check for mismatch → If str1[i] != str2[i], set flag = 1 and break the loop.

5.Return result → If flag == 0, return 0 (strings are the same); otherwise, return 1 
  

## Program:
```
/*
 C Program to compare two strings without using strcmp().
Developed by: 
RegisterNumber:  
*/
#include<stdio.h>
int compare(char[],char[]);
int main()
{
    char str1[20];
    char str2[20];
    scanf("%s",str1);
    scanf("%s",str2);
    int c= compare(str1,str2);
    if(c==0)
    printf("strings are same");
    else
    printf("strings are not same");
    return 0;
}
int compare(char a[],char b[])
{
    int flag=0,i=0;
    while(a[i]!='\0'&&b[i]!='\0')
    {
        if(a[i]!=b[i])
        {
            flag=1;
            break;
        }
        i++;
    }
    if(flag==0)
    return 0;
    else
    return 1;
    
}
```

## Output:
![image](https://github.com/user-attachments/assets/77d43056-54dd-4bc6-9fc9-1e819cf73f5a)



## Result:
Thus the program was executed and the output was verified successfully.
