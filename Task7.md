#include <stdio.h>
int main() {
	int length,width;
	float area,perimeter;
	printf("enter length of rectangle:");
	scanf("%d",&length);
	printf("enter the width of rectangle:");
	scanf("%d",&width);
    area=length*width;
	perimeter=2*(length+width);
	printf("area of rectangle=%.2f\n",area);
	printf("perimeter of rectangle=%.2f",perimeter);
	return 0;	
}
