# InvaderFDestiny
Personal Repository
#include <stdio.h>

unsigned int fact(unsigned int digit)
{
    while(digit)
    {
        if(digit==1)
            return 1;
        else
            return(digit*fact(digit-1));
    }
}
unsigned int strong_check(unsigned int num)
{
    unsigned int sum;
    while(num)
    {
        sum+=fact(num%10);
        num=num/10;
    }
    return sum;
}

int main()
{
    unsigned int num;
    scanf("%u",&num);
    (strong_check(num)==num)?printf("Strong Number"):printf("Not a Strong Number");

    
    return 0;
}
