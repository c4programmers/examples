/* example 065 – calculate the sum of numbers and exit with a negative number */
#include <stdio.h>

int main (void)
{
   int num=0, sum=0;

   printf("Sum of numbers - Entering a number < 0 aborts the program\n");
   printf("Enter a number: ");

   while(1) {
        scanf("%i",&num);

        if(num <0)
            break;

        printf("\nSum: %i\n",(sum += num));
        printf("Enter new number: ");
   }
   printf("END");

   return 0;
}
