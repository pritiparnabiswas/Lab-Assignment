DAY-1

//C programs to find size of the processor using pointer.
#include <stdio.h>

int main()
{
	int *ptr;
	printf("size of processor's word(pointer size):%zu bytes\n",sizeof(ptr));
	return 0;
}

//C program to find largest from 3 variable in one line.
#include <stdio.h>
int main()
{
	int a,b,c;
	printf("Enter no.");
	scanf("%d",&a);
	printf("Enter no.");
	scanf("%d",&b);
	printf("Enter no.");
	scanf("%d",&c);
	int largest=(a>b)?(a>c?a:c):(b>c?b:c);
	printf("The largest number is %d",largest);
	return 0;
}

//Swap two numbers without using odd and minus operators as well as third variables and pointers.
#include <stdio.h>
int main()
{
	int a,b;
	printf("Enter no.:");
	scanf("%d",&a);
	printf("Enter no.:");
	scanf("%d",&b);
	a^=b^=a^=b;
	printf("%d \n",a);
	printf("%d \n",b);
	return 0;
}

//find even or odd without modulus.
#include <stdio.h>
int main()
{
	int num;
	printf("Enter a number:");
	scanf("%d",&num);
	if (num&1)
	{
	  printf("%d is an odd number\n",num);
    }
    else
    {
      printf("%d is an even number\n",num);	
	}
	return 0;
}


DAY-2

//C program to check head or tail
#include <stdio.h>
int main()
{
	char head;
	char h;
	printf("Enter character for head:");
	scanf("%c",&head);
	if(head=='h')
	printf("Head");
	else
	printf("Tail");
	return 0;
}

//C program to check the leap year or not
#include <stdio.h>
int main()
{
	int Year;
	printf("Enter the Year:");
	scanf("%d",&Year);
	if(Year%400==0)
	printf("%d is Leap Year",Year);
	else if(Year%100!=0)
	printf("%d is not Leap Year",Year);
	else if(Year%4==0)
	printf("%d is Leap Year",Year);
	else
	printf("%d is not Leap Year",Year);
	return 0;
}

//C program to find that the roll number 20 is present or not.
#include <stdio.h>
int main()
{
	int roll_num;
	printf("Enter your roll number:");
	scanf("%d",&roll_num);
	if(roll_num==20)
	printf("The specified roll number 20 is present");
	return 0;
}

//C programs to print ADAMAS UNIVERSITY
#include <stdio.h>
int main()
{
	printf("Adamas University");
	return 0;
}

//C programs to find greatest of 3 number using ladder if-else
#include <stdio.h>
int main()
{
	int a,b,c;
	printf("Enter the value of three number:");
	scanf("%d %d %d",&a,&b,&c);
	if(a>b && a>c)
	{
		printf("a is maximum");
	}
	else if("b>a && b>c")
	{
		printf("b is maximum");
	}
	else
	{
		printf("c is maximum");
	}
	return 0;
}

//C programs to find greatest of 3 number using Nested if-else
#include <stdio.h>
int main()
{
	int a,b,c;
	printf("Enter the value of three number:");
	scanf("%d %d %d",&a,&b,&c);
	if (a>b)
	{
	if (a>c)	
	printf("a is maximum");
	else 
	printf("c is maximum");
    }
	else
	{
	if (b>c)	
	printf("b is maximum");
	else 
	printf("b is maximum");
	}
	return 0;
}
