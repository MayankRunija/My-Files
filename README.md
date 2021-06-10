# My-Files
code
#include<stdio.h>
#include<conio.h>

int add()

{
int a,b,c;



printf("Enter value of a and b:");
scanf("%d%d",&a,&b);
c=a+b;
printf("\n Addition of a and b is :%d",c);

getch();
return c;
}

int sub()
{
int x,y,z;



printf("Enter value of x and y:");
scanf("%d%d",&x,&y);
z=x-y;
printf("\n Subtraction of a and b is :%d",z);

getch();
return z;
}

int main()
{

 add(),sub();

getch();
return 0;
}

