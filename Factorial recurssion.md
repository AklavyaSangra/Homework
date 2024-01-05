    // Function to calculate factorial using recursion
    #include <stdio.h>
     // Function to calculate factorial using recursion
    int factorial(int n) {
    if (n == 0 || n == 1) {
        return 1;
    } else {
        return n * factorial(n - 1);
    }
    }

    int main() {
    int number;

    // Input the number
    printf("Enter a non-negative integer: ");
    scanf("%d", &number);

    // Check if the number is non-negative
    if (number < 0) {
        printf("Error: Factorial is not defined for negative numbers.\n");
    } else {
        // Calculate and display the factorial
        printf("Factorial of %d = %d\n", number, factorial(number));
    }

    return 0;
    }


Output of the progrma:


![image](https://github.com/AklavyaSangra/Homework/assets/146859465/c44de074-0ceb-4f47-a13b-e287326b4b68)




    
