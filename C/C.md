# Características
- C é uma [[Linguagem de alto nível|linguagem de programação de alto nível]]
- compilada
- usa o [[Paradigmas de programação#^49c57c| paradigma imperativo]]
- de propósito geral
	- sistemas embarcados
	- aparelhos pequenos
	- IoT
	- Arduíno
# Estrutura Básica
1. `#include <librabry>`
	- `stdio`
		- biblioteca básica
		- contém instruções de entrada e saída
	- outras
		- `math, time, stdlib`
2. `int main(){ } `
	- função main (principal)
	- onde fica o código
	- retorna um inteiro (int)
- não requer indentação, mas é importante para legibilidade 
	- tecnicamente pode ser escrita numa só linha
- Requer um `;` após cada comando 
3. `return 0`
	- retorno da função `main`
```C
#include <stdio.h>

int main(){
	// codigo aqui
	return 0
}
```
# Instruções primitivas
- `printf()` 
	- `printf("texto %<formato_da_saída> texto", <expressão>")`
	- escreve uma mensagem na tela 
	- `.<numero de casas decimais>`
		- usado para limitar o número de casas decimais de um float ou double
- `scanf()` 
	- `scanf("%<formato_da_entrada>, &<variável>")`
	- lê um dado inserido pelo usuário, armazenando-o em uma variável
- Instrução de atribuição
	- `<variável> = <valor> ou <expressão>`
		- Ex: `int Idade = 19`
		  
	- Atribui um valor a uma **[[variável]]** ou [[constantes|constante]]
# Operadores aritméticos
- \+
- \-
- \*
- / 
- % 
	- resto da divisão
- ++  
- \-\-
# Operadores relacionais
- == 
- != 
- <= 
- \>= 
- <
- \>
# Operadores lógicos
- && 
- || 
- !
# Comentários
- Destinados a compreensão do código
  `// COMENTÁRIO DE UMA LINHA`
  `/* COMENTÁRIO DE MÚLTIPLAS LINHAS */`
