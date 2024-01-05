Program to check if a number is prime or not using a while loop


    #include<stdio.h>

    int main()
    {
    int num,i=1,c=0;
    //inputr statement
    printf("Enter a number");
    scanf("%d",&num);
    //while loop statement
    while(i<=num)
    {
    //if else condition
    if(num%i==0)
    c++;
    i++;
    }
    if(c==2)
    printf("\n%d is a prime number",num);
    else
    printf("\n%d is not a prime number",num);
    
    return 0;
    }


Output of the program:


![image](https://github.com/AklavyaSangra/Homework/assets/146859465/78c12f9b-06a0-4a60-a807-372edbd1ffa9)
