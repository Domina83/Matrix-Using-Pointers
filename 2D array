#include<stdio.h>
int main()
{
int n,i,j;
    int a[3][3];
    int *p;
    printf("Enter any 9 numbers.\n");
    for(i=0;i<3;i++)
    {
    for(j=0;j<3;j++)
    {
        scanf("%d",&a[i][j]);
    }
    }
    p=& a [0][0];
    printf("The 9 numbers are:\n");
    for(i=0;i<3;i++)
    {
    for(j=0;j<3;j++)
    {
        printf("%d ",*(p+i*3+j));
    }
    printf("\n");
    }

    return 0;
}
