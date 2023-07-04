### Defina: o que é SRP?
### Cite e explique, um exemplo que pode ser utilizado o padrão SRP.

SRP - single resposibility principle - diz que uma classe deve ter apenas uma responsabilidade e função (ou funções similares).

Uma classe deve ter apenas um motivo para mudar, ou seja, a função principal daquela classe deve ser alterada para que seja necessário alterar a classe.

Um exemplo seria uma classe Retangulo que possui uma função calcularArea.
Por necessidade do cliente agora necessitamos também desenhar esse retângulo. Poderíamos criar uma nova função dentro da classe Retangulo chamada desenharRetangulo, porém isso estaria indo de encontro ao SRP da classe Retangulo que é calcular a sua área.

Portanto, poderíamos criar uma nova classe RetanguloGrafico, por exemplo, e dentro dessa classe implementar a função de desenhar o retangulo.
