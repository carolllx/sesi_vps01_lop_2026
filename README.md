# VPS01
## Verificação Prática  Somativa 01
Arquivos gerados durante a avaliação de lógica de programação, algoritmos e fluxogramas

## Tecnologias

|Tecnologia|Utilidade|
|:-:|-|
|Linguagem C|Desenvolvimento|
|IDE|Embarcadeiro **Dev C++**|
|[Draw.io](https://app.diagrams.net/)|Desenhar os *fluxogramas*|
|Bloco de notas|*portugol* lógica|

  ## Como testar
  - 1 clone o repositório
  - 2 abra os arquivos .c com DEvC++
  - 3 Pressione F11 para compilar executar

## Exemplo de código
```c
#include<stdio.h>
#include<windows.h>
void main(){
	SetConsoleOutputCP(CP_UTF8);
	char nome[20], sexo;
	int idade;
	printf("Digite seu nome, sexo m/f e idade\n");
	scanf(" %s %c %d", &nome, &sexo, &idade);
	if(sexo == 'm'){
		if(idade > 65){
			printf("O atendimento do paciente %s é prioritário", nome);
  		}else{
		  	printf("O atendimento do paciente %s é normal", nome);
  		}
   }else{
      if(idade > 60){
	  	printf("O atendimento do paciente %s é prioritário", nome);
      }else{
      	printf("O atendimento do paciente %s é normal", nome);
	  }
    }
    getch();
}
```
