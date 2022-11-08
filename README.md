# crack-code-C
TO FIND PRIME FACTORS OF A PARTICULAR NUMBER....
#include <stdio.h>
int primefactor(int num);
int main()
{
    int i,j,num,n;
    /* Input a number from user */
    printf("Enter any number to print Prime factors: ");
    scanf("%d",&num);
    n=primefactor(num);
    return 0;
}
int primefactor(int num)
{
    int i,j,n;
    for(i=2;i<=num;i++)
    {
        /* Check 'i' for factor of num */
        if(num%i==0)
        {
            /* Check 'i' for Prime */
            for(j=2; j<=i/2; j++)
            {
                if(i%j==0)
                {
                    return n;
                    break;
                }
            }
            {
               printf("%d\t",i);
            }
    }
}}
