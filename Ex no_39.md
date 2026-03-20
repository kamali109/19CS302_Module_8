# EX 39 C program to find sum of digits.

## AIM:
To write a C program to find sum of digits.

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
/*
C program to find sum of digits.
Developed by: KAMALI.S
RegisterNumber:  212222060109
*/
#include<stdio.h>
int main()
{
    int a,s,i,y=0;
    scanf("%d",&a);
    for(i=1;i<=5;i++)
    {
        s=a%10;
        y=y+s;
        a=a/10;
    }
    printf("%d",y);
}
```

## Output:
<img width="1127" height="167" alt="image" src="https://github.com/user-attachments/assets/f699acd1-eff0-454c-8d55-4fde34e7c075" />



## Result:
Thus the program was executed and the output was verified successfully.
