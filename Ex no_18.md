# EX 18 C program to find frequency of a character in the given input.
## DATE:
## AIM:
To write a C program to find frequency of a character in the given input.

## Algorithm
1.Input the string → Read the string str from the user.

2.Input the character → Read the character ch whose frequency needs to be counted.

3.Initialize frequency counter → Set frequency = 0 to track occurrences.

4.Iterate through the string → Loop through each character until '\0' (end of string).

5.Check for matches → If str[i] == ch, increment frequency.

6.Print the result → Display the final count of occurrences of ch in str. 

## Program:
```
/*
C program to find frequency of a character in the given input.
Developed by: 
RegisterNumber:  
*/
#include <stdio.h>
int main() {
    char str[100], ch;
    int i, frequency = 0;
    scanf("%s", str);
    scanf(" %c", &ch);
    for(i = 0; str[i] != '\0'; ++i){
        if(ch == str[i])
            ++frequency;
    }
    printf("%d", frequency);

    return 0;
}

```

## Output:
![image](https://github.com/user-attachments/assets/00a4b72e-d6a4-4604-bf73-73707525219a)



## Result:
Thus the program was executed and the output was verified successfully.
