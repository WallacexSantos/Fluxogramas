Receba o custo de fabricação de um item e o percentual de lucro desejado. Calcule e exiba o preço de venda sugerido

<img width="235" height="739" alt="lucro_desejado" src="https://github.com/user-attachments/assets/7e22c537-1a38-4b55-940a-efe5a616f6f7" />

Conversão para código em Portugol

programa
{
	
	funcao inicio()
	{
		escreva("Olá Mundo")
		real custo,lucro,preco,percentual
		/*Receba o custo de fabricação de um item e o percentual de lucro desejado. Calcule
e exiba o preço de venda sugerido.*/ 
  escreva ("\ndigite o custo de fabricação ") 
  leia (custo)
  escreva ("digite o percentual de lucro desejado ")
  leia (lucro) escreva ("porcento")
  percentual= lucro/100
  preco = custo + custo*percentual
 escreva ("\no preço sugerido é ", preco)
	}
}
