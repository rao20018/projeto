// código de cadastro com senha e login em c
#include<stdio.h>

int main () {

// captura da senha selecionado pelo úsuario

int senha;

printf("Digite a  senha : \n");

scanf("%i",&senha);

// comparado a senha selecionada pelo úsuario com senha verdadeira

if(senha ==116){

printf("a senha esta correta vamos continuar com seu cadastro \n");

// captura de dados para o cadastro
	
 char nome[20];
	
 int idade;

 printf(" digite seu nome : \n");
	
 scanf("%s",&nome);
	
	
 printf("digite sua idade : \n ");
	
 scanf("%i",&idade);
	
	
 printf("ola %s , sua idade e %i",&nome,idade);

}else {

printf("erro a senha esta incorreta \n");
}
	return 0;
 }
