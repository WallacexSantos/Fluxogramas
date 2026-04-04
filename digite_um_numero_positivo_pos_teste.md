Desenvolva um algoritmo que solicite ao usuário a digitação de um número inteiro. O programa deve verificar se o valor informado é negativo. Caso seja, deve continuar solicitando um novo número até que o usuário informe um valor positivo.

<img width="677" height="940" alt="digite_um_numero_positivo_pos_teste" src="https://github.com/user-attachments/assets/e800556a-3757-4ecb-9163-5068d8fe42b7" />

Conversão para código em Portugol

programa { funcao inicio() { inteiro numero escreva ("digite um numero ") leia (numero) se (numero<0){ faca { escreva ("por favor digite um numero positivo ") leia (numero)} enquanto (numero<0) }senao{ escreva ("ok,tudo certo") } } }
