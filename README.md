Program to calculate the sum of numbers (10 numbers max)
// If the user enters a negative number, the loop terminates
#include<stdio.h>
int main()
{
    float sum=0.0;
    int i, num;
    for(i=1;i<=10;++i)
    {
        printf("Enter a number ");
        scanf("%d",&num);
        printf("%d\n",num);
        if(num<0.0)
        {
            break;
        }

        sum+=num;
    }
    printf("Sum of number is %f :",sum);
    return 0;
}
