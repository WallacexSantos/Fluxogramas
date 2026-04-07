Faça um fluxograma e pseudocódigo para um programa que receba a idade de 10 pessoas e mostre: a. A quantidade de pessoas com menos de 18 anos. b. A quantidade de pessoas com idade maior ou igual a 18 anos.

<img width="998" height="1083" alt="maior_menor_de_idade_entre_10_pessoas" src="https://github.com/user-attachments/assets/0634f718-8b59-402a-ba97-8730952f0dcb" />

Conversão para código em Portugol

programa
{
	
	funcao inicio()
	{
      inteiro idade,contador,maior=0,menor=0
   
      para (contador=1; contador<=10; contador++){
 	escreva ("digite uma idade ")
      	leia (idade)
      	se (idade >=18){
      		maior++
      	}senao{
      	menor++
      	}
      }
	escreva ("maiores de idade ",maior)
	escreva ("\nmenores de idade ",menor)
}
}
