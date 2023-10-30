# Calculadora Java

Este é um projeto simples de calculadora em Java, composto por três partes principais: a classe `Calculadora`, um programa de teste `CalculadoraTeste`, e testes de unidade com JUnit em `CalculadoraJunitTest`.

## Calculadora.java

A classe `Calculadora` contém quatro métodos para realizar operações matemáticas simples:
- `somar`: Soma dois números inteiros.
- `subtrair`: Subtrai dois números inteiros.
- `dividir`: Divide dois números inteiros, tratando divisões por zero.
- `multiplicar`: Multiplica dois números inteiros.

**Exemplo de Uso:**

# CalculadoraTeste.java

O arquivo CalculadoraTeste.java contém um programa de teste simples que demonstra o uso da classe Calculadora para realizar operações matemáticas básicas, incluindo testes para adição, subtração, multiplicação e divisão.

public class CalculadoraTeste {
    public static void main(String[] args) {
        Calculadora calc = new Calculadora();
        int resultadoSoma = calc.somar(2, 3);
        System.out.println("Resultado da soma: " + resultadoSoma);
    }
}

# CalculadoraJunitTest.java

O arquivo CalculadoraJunitTest.java contém testes de unidade usando o framework JUnit. Ele testa a classe Calculadora em relação a operações matemáticas e verifica se os resultados estão corretos ou não.

@RunWith(JUnitPlatform.class)
public class CalculadoraJunitTest {
    // Métodos de teste usando anotações do JUnit
}

# Como Executar os Testes

Para executar os testes, siga as etapas a seguir:

1 - Certifique-se de que você tenha o Java e o JUnit instalados em seu ambiente.
2 - Abra o arquivo CalculadoraJunitTest.java em sua IDE ou editor Java.
3 - Execute os testes utilizando as ferramentas de teste de sua IDE ou execute-os via linha de comando.

Isso conclui a descrição do projeto da calculadora em Java, juntamente com informações sobre os principais arquivos e como executar os testes.


