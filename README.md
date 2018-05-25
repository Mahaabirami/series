#include <stdio.h>
#include <stdlib.h>

int main()
{
    printf("Enter  n\n");
    int i,n,t,a[5],b=1;
    scanf("%d",&n);
   printf("\nEnter the series diff\n");
   scanf("%d",&t);
   for(i=1;i<=n;i++)
   {
       printf("%d\n",b);
       b=b+t;

       printf("\n");
   }


    return 0;
}
