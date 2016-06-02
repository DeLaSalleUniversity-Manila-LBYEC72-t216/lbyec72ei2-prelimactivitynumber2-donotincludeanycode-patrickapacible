# lbyec72ei2-prelimactivitynumber2-donotincludeanycode-patrickapacible
```
#include <stdio.h>
#include <stdlib.h>


int main() {
	
	int x, vi, vf, t, a, d;
	int option, opt1, opt2;
	float ans1,ans2,ans3,ans4,ans5,ans6,ans7,r1,r2;
	
	printf("Main Menu\n\n");
	printf("1.) x = vi * t + (1/2)at^2\n2.) vf^2 = vi^2 + 2ax\n3.) Exit\n\n");
	scanf("%d", &option);
	if (option==1){
	printf("\nSolve for:\n1.) x\n2.) vi \n3.) t\n4.) a\n5.) Go Back\n\nEnter number: ");
	scanf("%d", &opt1);
	switch(opt1){	
	case 1:
	printf("Enter vi: ");
	scanf("%d", &vi);
	printf("Enter t: ");
	scanf("%d", &t);
	printf("Enter a: ");
	scanf("%d", &a);
	ans1=vi*t+a/2*t*t;
	printf("\nX is equals to %.2fm\n\n", ans1);
	return main();
	case 2:
	printf("Enter x: ");
	scanf("%d", &x);
	printf("Enter t: ");
	scanf("%d", &t);
	printf("Enter a: ");
	scanf("%d", &a);
	ans2=x/t-a/2*t;
	printf("\nvi is equals to %.2fm/s\n\n", ans2);
	return main();	
	case 3:
	printf("Enter vi: ");
	scanf("%d", &vi);
	printf("Enter x: ");
	scanf("%d", &x);
	printf("Enter a: ");
	scanf("%d", &a);
	d=vi*vi-2*a*-x;
	r1=(-vi+sqrt(d))/a;
	r2=(-vi-sqrt(d))/a;
	printf("\nt is equals to %.2fs and %.2fs\n\n", r1,r2);
	return main();
	case 4:
	printf("Enter x: ");
	scanf("%d", &x);
	printf("Enter t: ");
	scanf("%d", &t);
	printf("Enter vi: ");
	scanf("%d", &vi);
	ans3=2/t*(x/t-vi);
	printf("\na is equals to %.2fm/s^2\n\n", ans3);
	return main();
	case 5:
	return main();
	default:
	printf("Invalid input!\n\n");
	return main();
    }	
	}
    else if(option==2){
    printf("\nSolve for:\n1.) vf\n2.) vi \n3.) a\n4.) x\n5.) Go Back\n\nEnter number: ");
	scanf("%d", &opt2);	
	switch(opt2){
	case 1:
	printf("Enter vi: ");
	scanf("%d", &vi);
	printf("Enter x: ");
	scanf("%d", &x);
	printf("Enter a: ");
	scanf("%d", &a);
	ans4=sqrt(vi*vi+2*a*x);
	printf("\nvf is equals to %.2fm/s\n\n", ans4);
	return main();
	case 2:
	printf("Enter vf: ");
	scanf("%d", &vf);
	printf("Enter x: ");
	scanf("%d", &x);
	printf("Enter a: ");
	scanf("%d", &a);
	ans5=sqrt(vf*vf-2*a*x);
	printf("\nvi is equals to %.2fm/s\n\n", ans5);
	return main();
	case 3:
	printf("Enter vi: ");
	scanf("%d", &vi);
	printf("Enter vf: ");
	scanf("%d", &vf);
	printf("Enter x: ");
	scanf("%d", &x);
	ans6=(vf*vf-vi*vi)/(2*x);
	printf("\na is equals to %.2fm/s^2\n\n", ans6);
	return main();
	case 4:
	printf("Enter vi: ");
	scanf("%d", &vi);
	printf("Enter vf: ");
	scanf("%d", &vf);
	printf("Enter a: ");
	scanf("%d", &a);
	ans7=(vf*vf-vi*vi)/(2*a);
	printf("\nx is equals to %.2fm\n\n", ans7);
	return main();
	case 5:
	return main();
	default:
	printf("Invalid input!\n\n");
	return main();
	}
	}
	else if(option==3){
		return 0;
	}
	else{
		printf("Invalid Input!");
		return main();
	}

    
	return 0;
	
}
```
