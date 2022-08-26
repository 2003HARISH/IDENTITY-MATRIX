# IDENTITY-MATRIX
To check whether the matrix is an identity matrix or not 
#include <stdio.h>

int main() 
{
    int i,j,a[10][10];
    int n=0,r;
    printf("enter the number of rows:");
    scanf("%d",&r);
    printf("ENTER THE ELEMENTS OF THE ARRAY TO CHECK WHTEHER IT IS IDENTITTY OR NOT\n:");
    for(i=0;i<r;i++)
     for(j=0;j<r;j++)
       {
           printf("%d%d is:",i,j);
           scanf("%d",&a[i][j]);
           printf("\n");
       }
      printf("THE ELEMENTS GIVEN IN THE ARRAY IS\n");
       for(i=0;i<r;i++)
     {
        for(j=0;j<r;j++)
        printf("%d  ",a[i][j]);
        printf("\n");
     }
   for(i=0;i<r;i++)
   for(j=0;j<r;j++)
   {
       if(i==j)
       {
           if(a[i][j]==1)
           n++;
       }
   }
   
   if(n==r)
   printf("\n\nthe given matrix is an identity matrix");
   else
   printf("\nthe matriix is not identity matrix:");
   
    return 0;
}
