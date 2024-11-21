#include <stdio.h>
int main()
{
    float num1, num2;
    printf("Enter first number \n");
    scanf("%f", &num1);
    int operator;
    printf("1.Addition \n");
    printf("2.subtraction \n");
    printf("3.Multiplication \n");
    printf("4.Division \n");
    printf("Enter your choice \n");
    scanf("%d", &operator);
    printf("Enter second number \n");
    scanf("%f", &num2);
    switch (operator)
    {
    case 1:
        printf("The Addition of %f and %f is %f \n", num1, num2, num1 + num2);
        break;
    case 2:
        printf("The Subtraction of %f and %f is %f \n", num1, num2, num1 - num2);
        break;
    case 3:
        printf("The Multiplication of %f and %f is %f \n", num1, num2, num1 * num2);
        break;
    case 4:
        if (num2 =!0)
        {
            printf("The Division of %f and %f is %f \n", num1, num2, num1 / num2);
        }
        else
        {
            printf("ERROR 404: Division by 4 is not allowed");
        }
        break;
    default:
        printf("ERROR 404 \n");
        break;
    }
    return 0;
}
