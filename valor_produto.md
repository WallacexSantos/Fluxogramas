Algoritmo que lê o valor de um produto em dólar, a taxa de importação (60%) e o ICMS (18%). Exiba o valor final do produto em reais

<img width="160" height="743" alt="valor_produto" src="https://github.com/user-attachments/assets/91879f94-7975-4cec-a90c-eced0ed84c94" />

Conversão para código em Portugol

programa {
  funcao inicio() {
  //icms 18 porcento, taxa de importacao 60 porcento
    real valor_dolar,dolar
    escreva ("digite o valor do produto em dolares ")
    leia (valor_dolar)
    escreva ("digite a cotacao atual do dolar para reais ")
    leia (dolar)
    escreva ("o valor do produto em reais e ", (valor_dolar+valor_dolar*0.6+valor_dolar*0.18)*dolar)
  }
}
