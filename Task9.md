#include <stdio.h>
int main() {
	char userName[15];
	int userAge;
	printf("enter your name:\t");
	scanf("%s",userName);
	printf("enter your age:\t");
	scanf("%d",&userAge);
	printf("username is %s\n",userName);
	printf("user age is %d\n",userAge);
	return 0;
}
