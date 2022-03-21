// Write a program to print lower triangular matrix.
#include<stdio.h>
#include<conio.h>
void main()
{
    int a[3][3],i,j;
    for ( i = 0; i < 3; i++)
    {
        for ( j = 0; j < 3; j++)
        {
            scanf("%d",&a[i][j]);
        }
        
    }
    for ( i = 0; i < 3; i++)
    {
        for ( j = 0; j < 3; j++)
        {
            printf("%d\t",a[i][j]);
        }
        printf("\n");
    }
    printf("\n");
    for ( i = 0; i < 3; i++)
    {
        for ( j = 0; j < 3; j++)
        {
           if(i>j)
           {
             printf("%3d",a[i][j]);
           } 
        }
        
    }

    getch();
}
