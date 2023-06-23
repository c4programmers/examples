/* example 043 - macros */
#include <stdio.h>

/* In other words, if (a < b), if so, assign y the value b, otherwise the value a. */
#define MAX(a,b) ( a<b ? b : a )

int main(void)
{
    /* Variant 1 */
    int y, number1 = 2, number2 = 8;
    printf("The maximum is %d\n", MAX(number1, number2));

    /* Variant 2 */
    if(number1 < number2)
        y = number2;  // number2 is bigger
    else
        y = number1;  // number1 is bigger

    printf("The maximum is %d\n", y);
    return 0;
}
