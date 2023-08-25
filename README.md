# Classes de Figuras Geométricas

Este é um programa em C# que define uma hierarquia de classes para calcular áreas, perímetros e outras propriedades de figuras geométricas simples, como retângulos, círculos, quadrados, triângulos retângulos e triângulos equiláteros.

## Funcionamento

O programa consiste em várias classes que representam diferentes figuras geométricas. Cada classe tem métodos para calcular a área, o perímetro e outras propriedades específicas da figura.

- `Figuras`: Classe base que possui métodos para definir e obter a área e o perímetro de uma figura.

- `Retangulo`: Classe que herda de `Figuras` e representa um retângulo. Possui um método construtor que calcula a área, o perímetro e a diagonal do retângulo.

- `circulo`: Classe que herda de `Figuras` e representa um círculo. O método construtor calcula a área e o perímetro do círculo.

- `quadrado`: Classe que herda de `Retangulo` e representa um quadrado. O método construtor é herdado de `Retangulo`.

- `trianguloRetangulo`: Classe que representa um triângulo retângulo. Possui um método construtor que utiliza um retângulo para calcular a área, o perímetro e a hipotenusa do triângulo.

- `trianguloEquilatero`: Classe que herda de `Figuras` e representa um triângulo equilátero. O método construtor calcula a área, o perímetro e a altura do triângulo.

- `Programa`: Classe com o método `Main` que instancia e exibe informações sobre as diferentes figuras geométricas.

## Como usar

1. Certifique-se de ter o ambiente de desenvolvimento C# configurado em sua máquina.

2. Copie o código fornecido e cole-o em um arquivo `.cs`.

3. Compile e execute o programa.

4. O programa instanciará diferentes figuras geométricas e exibirá informações sobre elas, como nome, área, perímetro e outras propriedades.

## Observações

- Este código é um exemplo didático para ilustrar o uso de classes em C# para representar figuras geométricas. Ele pode ser expandido e aprimorado para incluir mais funcionalidades e figuras geométricas.

- O código poderia se beneficiar de comentários adicionais explicando a lógica por trás de certos cálculos e decisões de design.

- Certifique-se de considerar boas práticas de nomenclatura, formatação e organização do código ao desenvolver projetos mais complexos.
