 treinament Raiz//

#include <stdio.h>
#include <math.h>

//calculando raiz
//pow indica potência
/*
float n, qua, cub, raizq, raizc1, raizc2;

int main(){
//entrada
printf("Digite um numero\n");
scanf("%f", &n);
//calculos
qua=pow(n,2); //numero elevado a 2
cub=pow(n,3); //numero elevado a 3
raizq=sqrt(n); //raiz quadrada de n
raizc1=cbrt(n); //raiz cubica de n
raizc2 = pow(n,(1.0/3.0)); //raiz cubica de n
//comando de saida
printf("\nNumero ao quadrado e %.2f, e numero ao cubo e %.2f\n", qua,cub);
printf("\nRaiz quadrada e %.2f e a raiz cubica 1 %.2f\n", raizq, raizc1);
printf("\nRaiz cubica usando a funcao pow %.2f\n", raizc2);

return 0;
}
