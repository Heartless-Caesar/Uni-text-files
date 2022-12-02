### Análise de sensibilidade

- Restrições:

	- Isolar x2:
		A ordem das restrições determinará qual o mínimo e máximo
		de x2 com base no valor de x1.

	Ex: 1ª 4x1 + x2 = 10 & 2ª x1 + 2x2 = 9

	x2 = -4x1 + 10 -> mínimo -4
	x2 = 9/2 - x1/2 -> máximo -1/2


	- Dados esses valores é possível determinar o coeficiente angular, que por sua vez é representado por -(c1/c2):

	-4 <= -(c1/c2) <= -1/2

	- Segundo a análise de sensibilidade apenas um dos coeficientes é calculado por vez, logo temos que determinar um valor para o coeficiente que não será calculado, para representar este é necessário usar os valores da função objetivo inicial do problema:  
	
	F.O: Z = 5x1 + 2x2

	- Com isso iremos atribuir o valor de 5 = c1 e 2 = c2 quando formos calcular a que não recebe um valor, conforme o exemplo abaixo:

	-4 <= -(c1/2) <= -1/2 

	-4 <= -(5/c2) <= -1/2
	

	- Os cálculos são resolvidos conforme os exemplos abaixo:

	-4 <= -(c1/2) <= -1/2 {

	1) -c1/2 >= -4 -> 2*(-4) = (-c1 >= -8) (-1) -> c1 <= 8

	2) -c1/2 <= -1/2 -> 2 * -(1/2) -> (-c1 <= -1) (-1) -> c1 >= 1
	
	}

	-4 <= -(5/c2) <= -1/2 {

	1) 
	
	}