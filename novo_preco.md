Uma empresa tem uma lista de 10 produtos. Crie um loop que peça o preço antigo de cada um e exiba o novo preço com um reajuste de 8%.

<img width="605" height="508" alt="reajuste_de_preco" src="https://github.com/user-attachments/assets/cb993787-8bc9-460c-9432-18597f544295" />

Conversão para código em Portugol

programa
{
	
	funcao inicio()
	{
      real preco,produtos=0
      enquanto(produtos!=10){
      escreva("\ndigite o preco do produto ")
      leia (preco)
      escreva ("1o novo preco e ",preco+preco*0.08)
      produtos++
      }
	}
}
