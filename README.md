#include<stdio.h>
int main()
{
	long long int n,arr[100000],i,sum;
	scanf("%lld",&n);
	for(i=0;i<n;i++)
	{
		scanf("%lld",&arr[i]);
	}
	sum=arr[n-1]%10;
	if(sum%10==0)
	printf("Yes");
	else
	printf("No");
}
