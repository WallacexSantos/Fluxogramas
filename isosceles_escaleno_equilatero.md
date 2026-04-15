algoritmo que descobre se as medidas digitadas pelo usuário forma um triângulo e após isso informa se é um isósceles, escaleno ou escaleno.

<img width="462" height="758" alt="escaleno_isosceles_equilatero" src="https://github.com/user-attachments/assets/19bdb418-4b76-4a46-88ce-c3e3741b59a6" />

Conversão para código em Portugol

programa {
  funcao inicio() 
  {
real lado1,lado2,lado3
escreva ("digite o comprimento do primeiro lado ")
leia(lado1)
escreva ("\ndigite o comprimento do segundo lado ")
leia(lado2)
escreva ("\ndigite o comprimento do terceiro lado ")
leia(lado3)
se (lado1+lado2<lado3 ou lado2+lado3<lado1 ou lado1+lado3<lado2){
  escreva ("nao e um triangulo")
}senao{
  escreva ("e um triangulo")
  se (lado1==lado2 e lado2==lado3){
    escreva ("\ne um equilatero")
  }senao se (lado1!=lado2 e lado2!=lado3 e lado1!=lado3){
    escreva ("\ne um escaleno")
  }senao{
    escreva ("\ne um isosceles")
  }
} 
  }
}
