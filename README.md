#include <stdio.h>
int main(void){
int num;
printf("Enter your mark ");
scanf("%d",&num);
printf(" You entered %d", num); // printing outputs
	if (num>100) printf(" ! Wrong data ");
	else if(num >= 80){
	printf(" You got A grade and passed"); // printing outputs
		}
	else if ( num >=60){ // Note the space between else & if
		printf(" You got B grade and passed");
		}
	else if ( num >=40){
		printf(" You got C grade and passed");
		}
	else if ( num < 40){
		printf(" You Failed in this exam");
		}
return 0;
}
