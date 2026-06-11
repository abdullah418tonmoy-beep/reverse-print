#include <stdio.h>

int main()
{
    int  n,i;

    printf("Enter num: ");
    scanf("%d", &n);

    for (i=n;i>=0; i-=2)
    {
           printf(" %d \n",i);
    }


    return 0;
}
