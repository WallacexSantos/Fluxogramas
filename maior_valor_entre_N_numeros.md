Faça um fluxograma e pseudocódigo para um programa que, receba N números e ao final, mostre apenas o maior valor digitado.

<img width="750" height="1143" alt="maior_valor" src="https://github.com/user-attachments/assets/2e7e57dd-88ba-435d-bed8-e35f508676a6" />

Conversão para código em Portugol

programa
{
    funcao inicio()
    {
        real numero, maior
        caracter S_ou_N
        
        escreva("Digite o primeiro numero: ")
        leia(numero)
        maior = numero
        faca
        {
            escreva("Deseja digitar outro numero? (S=sim, N=nao) ")
            leia(S_ou_N)

            se (S_ou_N == 'S' ou S_ou_N =='s')
            {
                escreva("Digite um numero: ")
                leia(numero)

                se (numero > maior)
                {
                    maior = numero
                }
            }

        } enquanto (S_ou_N == 'S' ou S_ou_N =='s')

        escreva("O maior valor é ", maior)
    }
}
