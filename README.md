# Area
Area
#include<stdio.h>
#include<conio.h>

void main()
{
        
int a, b, c;
float output;
clrscr();


void addition(int a, int b)
{


}

void subtract(int a, int b)
{
    output = a - b;
    printf("Output:%d", output);

}

void muliply(int a, int b)
{
  c = a*b;
  printf("%d x %d = %d", a, b, c);

}

void division(int a, int b)
{
   output=b/a;
   printf("\n Division is %f",output);

}

printf("Enter First Number: ");
scanf("%d", &a);

printf("Enter Second Number: ");
scanf("%d", &b);

printf("Select The Operations :\nEnter 1 For Addition\nEnter 2 For Subtraction\nEnter 3 For Multiplication\nEnter 4 For Division");
scanf("%d", &c);

switch(c)
{

case 1:
addition(a,b);
break;

case 2:
subtract(a,b);
break;

case 3:
multiply(a,b);
break;

case 4:
division(a,b);
break;

default:
printf("You have entered invalid input. The program will close. ")
}

getch();
}
