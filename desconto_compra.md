Se um cliente comprar mais de 50 unidades de um produto, aplique um desconto de 15%. Caso contrário, exiba o preço normal.

<img width="659" height="724" alt="desconto_compra" src="https://github.com/user-attachments/assets/314b6914-1284-4cc6-84e5-af6374c82571" />

Conversão para código em Portugol

programa {
  funcao inicio() {
    real produtos,preco
    escreva ("digite a quantidade de produtos comprados ")
    leia (produtos)
    escreva ("digite o preco da compra ")
    leia (preco)
    se(produtos>50){
      escreva ("o preco da compra e ",preco*0.85 )
    }senao{ 
      escreva ("o preco da compra e ", preco)
    }
    }
  }
