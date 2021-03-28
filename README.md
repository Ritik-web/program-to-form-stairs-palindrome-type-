#include<stdio.h>
main()
{
	int n;
	printf("Enter number of lines: ");
	scanf("%d", &n);
	
	printf("\n");
	
	int i,j;
	for(i=1;i<=n;i++)
	{
		for(j=1;j<=i;j++)
		{
			printf("01");
			
		}
		printf("\n");
	}
}
