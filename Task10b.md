#include <stdio.h>
int main() {
	int a,b;
	printf("enter value of a:");
	scanf("%d",&a);
	printf("enter value of b:");
	scanf("%d",&b);
	printf("before swapping\n");
	printf("a=%d,b=%d\n",a,b);
	//swap
	a=a+b;
	b=a-b;
	a=a-b;
	printf("after swapping\n");
	printf("a=%d,b=%d\n",a,b );
	return 0;
}
