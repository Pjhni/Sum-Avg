# Sum-Avg
#define _CRT_SECURE_NO_WARNINGS
#include<stdio.h>

#include<stdio.h>
#include<conio.h>
void main()
{
	int num = 1;
	float avg;
	int i, sum = 0, count = -1;
	printf(" Press 0 to stop.\n ");
	for (i = 0;; i++)
	{
		printf(" Enter a number: ");
		scanf("%d", &num);
		count++;
		if (num == 0)
			break;
		else
			sum = sum + num;
	}
	
	printf("\n sum of above numbers=%d", sum);
	avg = sum/count;
	printf("\n avg of above numbers=%d", avg);
	getchar();
	getchar();
	

}
