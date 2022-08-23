# counting
This is a program for printing counting using for loop.
#include<stdio.h>
#include<conio.h>
void main()
{
	int a,i;
	printf("Enter value of a:");
	scanf("%d",&a);
	printf("Counting");
	for(i=1;i<=a;i++)
	{
		printf("\n%d",i);
	}
}
