# numeros-pares-impares
#include <stdio.h>
#include <math.h>

 int main()
{
    int i, n;
   for (i = 0; i<4; i++) {
      printf("\n\n Digite um numero:");
      scanf("%d", &n);
      
      if ((n%2) == 0) {
          printf("\n Numero par: %d", n);
      }
    } 
   return 0;
}
