#include <stdio.h>
int main() {
	int subject1,subject2,subject3;
	int totalMarks=300;  //100 marks per subject
	int obtainedMarks;
	float percentage;
	printf("enter marks in subject1:");
	scanf("%d", &subject1);
	printf("enter marks in subject2:");
	scanf("%d", &subject2);
	printf("enter marks in subject3:");
	scanf("%d", &subject3);
	obtainedMarks=subject1+subject2+subject3;
	percentage = ((float)obtainedMarks / totalMarks) * 100;
	printf("obtainedMarks=%d\n",obtainedMarks);
	printf("totlaMarks=300\n",totalMarks);
	printf("the percentage is=%.2f%%\n",percentage);
	return 0;
}
