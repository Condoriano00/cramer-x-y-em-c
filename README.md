# Cramer X & Y em C

Programa em C desenvolvido para resolver um sistema linear de equações utilizando-se da regra de Cramer.
O programa resolve e fornece a solução de equações com incógnitas x e y.

Dado o sistema:

	2x + 8y = 0
	9x + 6y = 15

x = Dx / D

y = Dy / D

D:

	2      8
	9      6    

O determinante é dado por D = 2*6 – 8*9 →12 – 72 → – 60

Verificamos que o D ≠ 0, então o sistema é possível e determinado.

A solução desse sistema será dada por:
	
Onde Dx e Dy são obtidos trocando a coluna x ou a y (de acordo com a que está calculando) pela coluna dos termos independentes. Observe:

Dx:
	 
	0         8
	15        6


	0*6 – 8*15 = – 120

	x = Dx / D = – 120/– 60 = 2
	x = 2

Dy:

	2      0
	9     15

	2*15 – 0*9 = 30

	y = Dy / D = 30 / – 60 = – 0,5
	y = – 0,5

	S{-0,5 , -0,5}

![cramer2](https://user-images.githubusercontent.com/59848966/82281715-66e2a780-9968-11ea-98b2-d7cd444160b7.png)

Se o sistema for impossível (onde determinante igual a 0):

Equação:

	3x – 3y = – 9
	3x – 3y = 15

	D = 0

![cramer4](https://user-images.githubusercontent.com/59848966/82279822-c68a8400-9963-11ea-9b04-c906d22497a3.png)

Menu:

![cramer1](https://user-images.githubusercontent.com/59848966/82277846-42ce9880-995f-11ea-961f-0c187e55da24.png)

Copyright:

![cramer3](https://user-images.githubusercontent.com/59848966/82277850-43ffc580-995f-11ea-9214-ae4b03309de0.png)

Bibliografia (das quais derivam os exemplos):

https://mundoeducacao.uol.com.br/matematica/solucao-um-sistema-utilizando-regra-cramer.htm

https://mundoeducacao.uol.com.br/matematica/classificacao-um-sistema-linear.htm

Feito em conjunto com Miguel Chiarello Fernandes e Matheus Jediel Ferreira.
