Receba o status de 15 faturas (1 para Pago, 2 para Pendente). Ao final, exiba quantas faturas estão pendentes.

<img width="423" height="610" alt="fatura_pendente" src="https://github.com/user-attachments/assets/bbe1d815-1e0e-42c0-954c-a5ad14b86f5f" />

Conversão para código em Portugo

programa
{
	
	funcao inicio()
     {
     inteiro pago=0,pendente=0,faturas=0,status=0
     enquanto (status!=15){
     escreva ("digite o status da fatura (1 para pago, 2 para pendente) ")
     leia (faturas)
     se(faturas==1){
     pago++
     status++
     }senao{
   	pendente++
   	status++
     }
	}
	escreva ("a quantidade de faturas pagas sao ",pago)
	escreva ("\na quantidade de faturas pendentes sao ",pendente)
}
}
