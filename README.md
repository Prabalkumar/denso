# denso
#include<stdio.h>
main()
{
int dis,count=0;
float amt;
printf("Enter the amount and discount");
scanf("%f%d",&amt,&discount);
while(amt>0)
{ 
if(amt>=1)
{
amt=amt-(amt*(dis/100));

    count++;
}
}
printf("\n%d",count);

}
