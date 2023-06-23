/* example 030 - complex datatypes */
#include <stdio.h>
#include <complex.h>

const double PI = 3.141592653589793238;
int main()
{
   double complex z = 2 + 1.5*I;
   double x = creal(z);        // Real part
   double y = cimag(z);        // Imaginary part
   double radius = cabs(z);    // Length of Z
   double argument = carg(z);  // Angle in rad

   printf("cartesian(x, y): (%4.2f, %4.2f)\n", x, y);
   printf("polar(r, rad): (%4.2f, %4.2f)\n", radius, argument);
   printf("polar(r, deg): (%4.2f, %4.2f)\n", radius, argument*180/PI);
}
