/* example 070 – example with switch-case, break and default */
#include <stdio.h>

int main(void)
{
    int score;
    printf("Enter your achieved score (0 to 10): ");
    scanf("%i",&score);

    if((score > 10) || (score <= 0))
	   printf("\nError, please insert a valid score ");

    else {
        switch(score) {
            case 10: printf("\nResult: \tA");
                break;
            case 9: printf("\nResult: \tB");
                break;
            case 8: printf("\nResult: \tC");
                break;
            case 7: printf("\nResult: \tD");
                break;
            default: printf("\nResult: \tF");

            printf("\n\n\nKey:\n10=A\n9=B\n8=C\n7=D\n<7=F\n\n");
        }
    }
    return 0;
}
