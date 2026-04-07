Faça um fluxograma e pseudocódigo para um programa que mostre a tabuada da multiplicação dos números de 1 a 10.

<img width="790" height="587" alt="tabuada" src="https://github.com/user-attachments/assets/e14c196f-2d9b-40bf-ab9b-0adadf2eac73" />

Conversão para código em Portugol

programa
{
	funcao inicio()
	{
		inteiro numero, contador
		para ( contador = 1; contador <= 10; contador++ )
		para (numero=1 ; numero<=10 ; numero++)
		{
			escreva("\n", numero, "*", contador, " = ", numero * contador)
		}
	}
}
