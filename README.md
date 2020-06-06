#include<stdio.h>
#include<conio.h>
void main()
{
int a,b,c,large;
clrscr();
printf("Enter 3 numbers");
scanf("%d%d%d",&a,&b,&c);
large=a>b?a>c?a:c:b>c?b:c;
printf("%d",large);
getch();
}
