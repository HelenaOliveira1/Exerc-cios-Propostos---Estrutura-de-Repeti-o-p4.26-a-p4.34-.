# Exercícios Propostos-Estrutura de Repetição (p4.26 a p4.34).

Exercícios Propostos - 4.3. Estrutura de Repetição

p4.26 - Qual a utilidade da estrutura de repetição?
	A estrutura de repetição serve para que uma série de comandos seja repetidamente executada até que uma condição seja satisfeita dentro do Algoritmo, de forma automática.
	Ex.: enquanto {condição} faça    
	{enquanto a condição for verdadeira o bloco de comados será executado}

p4.27 - Em que consiste o controle de repetições por contador?
	O controle de repetições por contador é utilizado quando se sabe previamente a quantidade de vezes que um bloco de comandos precisará ser repetido. O contador é uma variável do tipo inteira, e para que seja executada, antes do laço deve-se pôr o valor 1, como ponto de partida para as repetições, sendo este adicionado ao conteúdo da própria variável, depois é necessário colocar o número de vezes que deve repetir-se o bloco de comandos. 
	Ex.: para CONT de 1 até 20 faça 
	{ o "até" significa <= (menor igual que)}

p4.28 - Em que consiste o controle de repetições por flag?
	O controle por flag ocorre quando não conhecemos o total de repetições que serão necessárias, portanto será determinado por um valor de uma variável que será lido.
		Ex.: 
		
		Algoritmo Exemplo
		Var
			num: inteiro
		num <- 10
			leia num
			enquanto num # 20 faça
				num <- num + 1
				leia num
			fim-enquanto

p4.29 - Faça o acompanhamento da execução do algoritmo abaixo e preencha a Tabela de Variáveis:
	
	TRECHO DE ALGORITMO
	N <- 0
	L <- 1
	enquanto N # 6 faça 
		L <- L * (-1)
		N <- N + 1 
		se L > 0
			então escreva N
		fim -se
	fim -enquanto 
	
	
	TABELA DE VARIÁVEIS
	| N | L |   N != 6   | Saída | 
	| 0 | 1 | Verdadeiro |  / |
	| 1 |-1 | Verdadeiro |  2 |
	| 2 | 1 | Verdadeiro |  / |
	| 3 |-1 | Verdadeiro |  4 |
	| 4 | 1 | Verdadeiro | /  |
	| 5 |-1 | Verdadeiro | 6  |
	| 6 | 1 |   Falso    | /  |

p4.30 - Faça um algoritmo que mostre todos os números inteiros de 1 a 50.
	
	Algoritmo Numeros_Inteiros
	{Escrever todos os números inteiros de 1 a 50}
	Var
		num: inteiro 
	Inicio
		num <- 1
	 	para CONT de 1 até 50 faça
	 		escreva num
	 		num <- num + 1
		fim -para
	Fim

p4.31 - Faça um algoritmo que mostre todos os números inteiros pares de 2 a 100.

	Algoritmo Numeros_Inteiros_Pares
	{Escrever todos os números inteiros pares de 2 a 100}
	Var
		num: inteiro
	Inicio
		num <- 2
		enquanto (num <= 100) faça
			escreva num
			num <- num + 2
		fim -enquanto
	Fim

p4.32 - Faça um algoritmo que gere a seguinte série: 10, 20, 30, 40, ..., 990, 1000.

	Algoritmo Série_dez_em_dez
	Var
		num : inteiro
	Inicio
		num <- 10
		enquanto (num <= 1000) faça
			escreva num
			num <- num + 10
		fim -enquanto
	Fim

p4.33 - Faça um algoritmo para gerar e exibir os números inteiros de 100 até 1, decrescendo de 1 em 1.

	Algoritmo Numeros_decrescendo
	Var
		num: inteiro
	Inicio
		num <- 100
		enquanto (num # 1) faça 
			escreva num
			num <- num - 1
		fim -enquanto
		escreva num
	Fim

p4.34 - Faça um algoritmo que leia um número N, some todos os números inteiros de 1 a N, e mostre o resultado obtido.

	Algoritmo Soma_com_N
	Var
		N, num, soma: inteiro
	Inicio
		escreva ("Informe um número: ")
		leia N 
		num <- 1
		soma <- 0
		enquanto (num <= N) faça
			soma = soma + num
			num = num + 1
		fim –enquanto
		escreva (“A soma dos números é:”, soma)
	Fim
