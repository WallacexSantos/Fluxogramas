Faça o fluxograma e pseudocódigo para um programa que mostre a quantidade de números entre 1000 e 2000 e que, quando divididos por 11, produzam resto igual a 5.

<img width="912" height="675" alt="resto_5" src="https://github.com/user-attachments/assets/de1d1e8e-027e-49ce-8b16-cafb1356cd22" />

Conversão para código em Portugol

programa
{
	funcao inicio()
	{
		inteiro numero = 1000,contador = 0
		
		enquanto (numero <= 2000)
		{
			se (numero % 11 == 5)
			{
				escreva("\n", numero)
				contador++
			}
			numero++
		}
		
		escreva("quantidade: ", contador)
	}
}
