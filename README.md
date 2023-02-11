# Assignment-submission-1
Write a program to accept two integers and check whether they are equal or not


#include <stdio.h>
void main()
{
    int i, j;
 
    printf("Input the values for Number1 and Number2 : ");
    scanf("%d %d", &i, &j);
    if (i == j)
        printf("Number1 and Number2 are equal\n");
    else
        printf("Number1 and Number2 are not equal\n");
}
