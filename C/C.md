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
	- escreve uma mensagem na tela 
- `scanf()`  
	- lê um dado inserido pelo usuário, armazenando-o em uma variável
- 