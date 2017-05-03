# start
#include<stdio.h>
void star(int n);
void space(int n);
int main()
{
    int row,i;
    printf("please input a intager:");
    scanf("%d",&row);
    for(i=1;i<=row;i++)
    {
        space(row-i);
        star(2*i-1);
        printf("\n");
    }
    printf("\n");
    return 0;
}
void star(int n)
{
    int i;
    for(i=1;i<=n;i++)
    {
        printf("*");
    }
}
void space(int n)
{
    int i;
    for(i=1;i<=n;i++)
    {
        printf(" ");
    }
}
