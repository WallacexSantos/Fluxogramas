Faça um fluxograma e pseudocódigo que receba um número e mostre a tabuada da multiplicação para esse número digitado

<img width="540" height="775" alt="tabuada" src="https://github.com/user-attachments/assets/54eaa642-bbae-4862-a837-62fdee83241f" />

Conversão para código em Portugol

{
	funcao inicio()
	{
		inteiro numero, contador

		escreva("Digite um numero: ")
		leia(numero)

		para (contador = 1; contador <= 10; contador++)
		{
			escreva("\n", numero, "*", contador, " = ", numero * contador)
		}
	}
}
