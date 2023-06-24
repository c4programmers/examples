/* example 087 – the while-loop */
#include <stdio.h>
#include <math.h>

int main(void)
{
   int clearPuffer;
   double number;

   printf("The program calculates the square of a number ");
   printf("[Entering 0 terminates the program]\n");
   printf("Enter a number: ");
   scanf("%lf",&number);

   while (number != 0) {
      printf("The square of %lf = %lf\n",number, number*number);
      printf("The sine of %lf = %lf\n",number, sin(number));
      printf("The cosine of %lf = %lf\n",number, cos(number));
      printf("Enter a number: ");
      scanf("%lf",&number);
   }

   // *1. Terminate the input stream
   while ((clearPuffer = getchar()) != EOF && clearPuffer != '\n');

   return 0;
}
