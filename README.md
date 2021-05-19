#include <stdio.h>
int main()
{
     int size[5];
     int i, n, sum = 0;

     printf("Size of an array: ");
     scanf("%d", &n);

     for(i=0; i<n; ++i)
     {
          printf("Element %d: ",i+1);
          scanf("%d", &size[i]);
          
          // adding integers entered by the user to the sum variable
          sum += size[i];
     }

     printf("Sum of all array elements = %d", sum);

     return 0;
}
