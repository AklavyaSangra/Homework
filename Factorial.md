Write a c code to find the factorial of the numbers.


#include <stdio.h>

int main() {
    
   int num = 5;

  
   if (num < 0) {
    printf("Factorial is not defined for negative numbers.\n");
    } 
    else
    {
    int result = 1;

  for (int i = 1; i <= num; ++i) {
  result *= i;
   }

  
  printf("Factorial of %d = %d\n", num, result);
   }
  
  return 0;
}


Output of the program:



