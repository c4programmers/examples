/* example 036 - implicit typecasting */
#include <stdio.h>

int main(void)
{
   int float_to_int = 3.8;	// Values after the decimal point are ignored
   char int_to_char = 275;	// High-order bits are truncated (0001 0001 0011)
   int x = int_to_char;      	// x = 0001 0011 = 19
   float char_to_float = 'A';	// The ASCII Code for A = 65
   double long_to_double = 123456789;

   printf("float to int: %d\n", float_to_int);
   printf("int to char: %i\n", x);
   printf("char to float: %f\n", char_to_float);
   printf("long to double: %lf\n", long_to_double);

   return 0;
}
