 Peça ao usuário para digitar os valores de todas as vendas do dia. O loop encerra quando o usuário digitar "0". Ao final, exiba o total faturado.

 <img width="387" height="507" alt="vendas_do_dia" src="https://github.com/user-attachments/assets/f201168e-12bd-41a8-9de6-0f3030b7508b" />
 
Conversão para código em Portugol

programa {
  funcao inicio() {
    real valor,vendas=0
    escreva ("digite o valor da venda (0 para parar) ")
    leia (valor)
    enquanto(valor!=0){
      vendas=vendas+valor
       escreva ("digite o valor da venda (0 para parar) ")
    leia (valor)
    }
      escreva ("o total de vendas foi ",vendas)
  }
}
