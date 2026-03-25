Leia o salário de um cliente e o valor da parcela de um empréstimo. Se a parcela for maior que 30% do salário, exiba "Crédito Negado"; caso contrário, "Crédito Aprovado".

<img width="342" height="746" alt="emprestimo" src="https://github.com/user-attachments/assets/2e3bb61b-29c7-4a5d-b244-7ec7a19a1119" />

Conversão para código em Portugol

programa {
  funcao inicio() 
  {
    real salario,parcela
    escreva ("digite o seu salario ")
    leia (salario)
    escreva("digite o valor da parcela ")
    leia (parcela)
     se (salario*0.3<parcela) {
      escreva ("credito negado")
     }senao{
    escreva ("credito aprovado")
  }
}
}
