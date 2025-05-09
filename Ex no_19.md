# EX 19 C PROGRAM TO FIND SMALLEST AMONG THREE ELEMENTS
## AIM:
     To write a program to find the smallest number among three numbers.
## Algorithm
1.	Start.
2.	Define a variables a,b,c.
3.	Write program to find the smallest among the three numbers.
4.	Read the value using scanf.
5.	Ask the user to make an input.
6.	Print out the answer.
7.	End.

## Program:
```
#include<stdio.h>
 int main()
{
int a,b,c;
 scanf("%d%d%d",&a,&b,&c);
 if(a<b && a<c)
{
printf("%d is the smallest number.",a);
}
else if(b<a && b<c)
{
printf("%d is the smallest number.",b);
}
else
{
printf("%d is the smallest number.",c);
}
}

```

## Output:

![image](https://github.com/user-attachments/assets/67abd5ac-c6e5-40f6-94b0-bdf73ca039c3)


## Result:
Thus the program was executed and the output was verified successfully.
