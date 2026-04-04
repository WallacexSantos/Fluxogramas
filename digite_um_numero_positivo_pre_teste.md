Desenvolva um algoritmo que solicite ao usuário a digitação de um número inteiro. O programa deve verificar se o valor informado é negativo. Caso seja, deve continuar solicitando um novo número até que o usuário informe um valor positivo.

<img width="604" height="923" alt="digite_um_numero_positivo_pre_teste" src="https://github.com/user-attachments/assets/44e889ea-8308-439b-82ed-99aa5688244b" />

Conversão para código em Portugol

programa
{

funcao inicio()
{
	inteiro numero
	escreva ("digite um numero ")
	leia (numero)

	enquanto (numero < 0)
	{
		escreva ("por favor digite um numero positivo ")
		leia (numero)
	}

	escreva ("ok, tudo certo")
}

}
