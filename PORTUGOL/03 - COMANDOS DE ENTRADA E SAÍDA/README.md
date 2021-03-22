# COMANDOS DE ENTRADA E SAÍDA

## COMANDO DE SAÍDA
Serve para exibir algum dado na tela para o usuário ou exibir uma mensagem para instruir o usuário.
Comando: 

	- escreva("") 
	- escreva("\n") este pula uma linha

## COMANDO DE ENTRADA
Serve para que possamos receber algo que é digitado pelo usuário.
Comando: 

	- Leia()

### Exemplo:

Se quiséssemos criar um algoritmo que recebe o nome do usuário


programa{
	funcao inicio(){
		cadeia nome
		escreva("Informe o seu nome: \n") //Exibe a mensagem na tela solicitando algo para o usuário
		leia(nome) // o que o usuário digitou ficará armazenado dentro da variável nome
	    	escreva(nome)//Mostra o nome que o usuário digitou
	}
}
