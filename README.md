/* This program is to accept a no and display message whether it is positive or negative using
if...else */
#include<stdio.h>
#include<conio.h>

void main()
{
float no;
clrscr();
printf("\n Enter a no?");
scanf("%f", &no);

if(no < 0)
{
 printf("\n %.2f is a Negative Number", no);
}
else
{
 printf("\n %.2f is a Positive Number", no);
}
getch();
}
