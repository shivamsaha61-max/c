#include <stdio.h>
#include <math.h>

int main()
{
    float pi=3.14 ;
    float volume;
   int rad , higt ; //rad = radious, higt=height
   printf("Enter radious:");
   scanf("%d", &rad);
   printf("\nEnter height:");
   scanf("%d",&higt);
   volume=pi*rad*rad*higt;
   printf("\nThe volume is:%f", volume);
   
   

    return 0;
}
