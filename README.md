#include<stdio.h>
#include<conio.h>
main()
{
 int array[3][3],i,j;
 clrscr();
 printf("enter the number:\n");
 for(i=0;i<3;i++)
  {
    for(j=0;j<3;j++)
    scanf("%d",&array[i][j]);
    }
    printf("proudecte of :\n");
    for(i=0;i<3;i++)
     {
       for(j=0;j<3;j++)
       printf("%d",array[i][j]);
       }
       getch();
       }
