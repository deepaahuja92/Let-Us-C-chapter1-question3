//# Let-Us-C-chapter1-question3
#include<stdio.h>
int main()
{
int mark,sum=0;
printf("Enter marks obtained in 1st subject:");
scanf("%d",&marks);
sum+=marks;
printf("Enter marks obtained in 2nd subject:");
scanf("%d",&marks);
sum+=marks;printf("Enter marks obtained in 3rd subject:");
scanf("%d",&marks);
sum+=marks;printf("Enter marks obtained in 4th subject:");
scanf("%d",&marks);
sum+=marks;
printf("Enter marks obtained in 1st subject:");
scanf("%d",&marks);
sum+=marks;
float percentage=sum/5.0;
printf("Percentage=%f",percentage);
printf("Aggregate marks=%d",sum);
return 0;
}
