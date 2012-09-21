//3742.Feynman.c
//spoj... solução de presente para vc ^^
// \o

#include <stdio.>

int main ()
{
  int n, aux, solucao;
  
    while(1)
    {
      scanf("%d",&n);
      if (!n) break;
      solucao=0;
        while(n>0)
        {
          aux=n*n;
          solucao+=aux;
          n--;
        }
      printf("%d\n",solucao);
  
    }

  return 0;

}