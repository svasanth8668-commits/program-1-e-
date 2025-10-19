# program-1-e-
C module 1

EX NO-1)e)-To calculate the total, average and percentage of marks in 4 subjects. 

Date:19/10/2025
Name:VASANTH S
Ref no:25017538


AIM:
To write a C program to calculate total, average and percentage of marks in 4 subjects.

ALGORITHM:
1)Get the input marks from the user.
2)calculate the total ,average and percentage.
3)print the outputs using printf() function.

PROGRAM:
```
#include <stdio.h>
int main()
{
    int num1,num2,num3,num4;
    float tot,avg,percent;
    scanf("%d %d %d %d",&num1,&num2,&num3,&num4);
    tot=num1+num2+num3+num4;
    avg=tot/4;
    percent=tot/4;
    printf("Total marks = %.2f \n",tot);
    printf("Average marks = %.2f \n",avg);
    printf("Percentage = %.2f",percent);
}
```

OUTPUT:

<img width="635" height="314" alt="Screenshot 2025-10-19 210212" src="https://github.com/user-attachments/assets/c87123cc-cc1a-4f88-a205-5a91822c35b1" />

RESULT:
Thus the C program to calculate the total, average and percentage of marks in 4 subjects is successfully executed.











