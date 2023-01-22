```C
/* Escrever programa que receba a medida de dois ângulos
internos de um triângulo, calcule e mostre a medida do terceiro ângulo;
sabendo que a soma dos ângulos internos de um triângulo é 180.
*/

#include <stdio.h>

int main(){
	float angulo1, angulo2;
	scanf("%f %f", &angulo1, &angulo2);
	printf("a medida do terceiro angulo eh %.2f", 180 - angulo1 - angulo2);
	return 0; 
}
```

```C
/* Escrever programa para ler: peso atual, peso
ideal e perda mensal; e exibir em quantos dias a pessoa
alcançará o peso ideal.  
*/

#include <stdio.h>

int main(){
	float pesoAtual, pesoIdeal, perdaMensal;
	printf("Digite o peso atual em kg:");
	scanf("%f", &pesoAtual);
	printf("Digite o peso ideal em kg:");
	scanf("%f", &pesoIdeal);
	printf("Qual a perda mensal?");
	scanf("%f", &perdaMensal);
	printf("voce vai atingir seu peso ideal em %.f dias", (pesoAtual - pesoIdeal) / perdaMensal * 30);
	return 0; 
}
```

```C
/* Escrever um programa para ler o ano em que a criança toma a 1ª dose e a periodicidade (intervalo em anos) da vacina e exibir em que outros anos a criança deve tomar as próximas doses desta vacina, sabendo que são 4 doses ao total */

#include <stdio.h>

int main(){
	int anoDose1, intervalo;
	printf("Que ano foi a primeira dose da vacina? ");
	scanf("%d", &anoDose1);
	printf("Qual o intervalo de vacinação? ");
	scanf("d", &intervalo);
	printf("As proximas doses serao em %d, %d, e %d", anoDose1 + intervalo, anoDose1 + intervalo*2, anoDose1 + intervalo*3);
	return 0; 
}
```
