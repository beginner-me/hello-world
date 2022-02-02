# hello-world
This is my first repository
#include<stdio.h>
int main()
{
	int num = 5,sum=0;
	do
	{
		printf("current value of n is : %d \n" ,num);
		sum = sum + num;
		num--;
		
	}
	while(num>0);
	printf("\n sum = %d", sum);


}
