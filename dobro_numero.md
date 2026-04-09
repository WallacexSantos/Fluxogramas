Algoritimo que calcula o dobro do número digitado pelo usuário.

<img width="260" height="573" alt="dobro_numero" src="https://github.com/user-attachments/assets/00f4d9af-754c-49b2-b9dc-f01484d7f07c" />

Conversão para código em Portugol 

programa {
  funcao inicio(){
    real numero, sim_ou_nao=1
    enquanto (sim_ou_nao==1){
    escreva ("digite um numero ")
    leia (numero)
    escreva ("o dobro do numero digitado e ",numero*2)
    escreva ("\ndeseja digitar mais um numero? (digite 1 para sim e 2 para nao) ")
    leia  (sim_ou_nao)
    }
  }
}
