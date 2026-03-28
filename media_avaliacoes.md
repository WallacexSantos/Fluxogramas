Crie um fluxo que receba notas de 1 a 5 de clientes. O programa deve parar após 20 avaliações e exibir a média final de satisfação

<img width="445" height="681" alt="media_avaliacoes" src="https://github.com/user-attachments/assets/1ddb3ff0-e0b6-4fcb-9c32-a44e6c8ae636" />

Conversão para código em Portugol

programa
{
	
	funcao inicio()
	{
    real nota,avaliacoes=0,total=0
    escreva ("digite uma nota de 1 a 5 ")
    leia (nota)
    avaliacoes ++
    enquanto (avaliacoes!=20){
    	escreva ("digite uma nota de 1 a 5 ")
    leia (nota)
    avaliacoes ++
    total=total+nota
    }
    escreva ("a media das avaliacoes e ", total/20)
}
}
