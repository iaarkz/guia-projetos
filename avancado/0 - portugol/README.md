# Portugol

## 1. Introdução à Programação

No [Portugol WebStudio](https://portugol-webstudio.cubos.io/ide) a priori temos a entrada e saídas de dados. A entrada de dados permite que o usuário pode digitar números, palavras, frases, entre outros. Já saída de dados permite ao algoritmo exibir dados na tela do computador.

O comando para entrada de dados é:

```
 leia (nome_da_variavel)
```

O comando para saída de dados é:

```
escreva("Escreva o texto a ser digitado")
```

## 2. Declarações de variáveis

Quando criamos uma variável, simplesmente separamos um espaço de memória. O sinal de igual "=" é o símbolo da atribuição no Portugol.

Algumas formas de declarações de variáveis, são elas:

- inteiro: Declara a variável a um valor do tipo inteiro. Exemplo:

```
   inteiro soma = 25
```

- real: Declara a variável a um valor do tipo real, isto é, não pertencem aos números inteiros. Exemplo:

```
 real media = 7.561
```

- cadeia: Declara a variável do tipo string. Ou seja, um texto ou uma quantidade grande de caracteres. Exemplo:

```
cadeia aluno = "Marcelo"

cadeia aluna = "Larissa"
```

- caracter: Declara a variável que contém uma informação de apenas **UM** carácter alfanumérico ou especial. Exemplo:

```
 caracter opcao = "+"
```

- logico: Declara a variável para exibir se determinada condição é verdadeira ou falsa. Essa operação é também chamada de operação booleana. Exemplo:

```
logico valor = 3 < 4
```

- const: Declara a variável a um valor de constante. Tal valor de variável **não** pode ser alterado até o final do código.

```
const real PI = 3.1415926535
```

### _Exercícios Resolvidos_

1. Faça um programa em Portugol WebStudio que realize a declaração dos tipos de dados entradas em inteiro, real, cadeia, caracter e booleano. Posteriormente, mostre os seus dados de saídas.

```
programa
{
	funcao inicio()
	{
        inteiro x = 10
        real raio = 2.5
        cadeia nome = "Marcelo"
        caracter alternativa = 'a'
        logico valor = 3>4

        escreva(" x = ", x)
        escreva("\n raio = ", raio)
        escreva("\n nome = ", nome)
        escreva("\n alternativa = ", alternativa)
        escreva("\n 3>4? = ", valor)
	}
}
```

## 2.1 Operações Matemáticas

Utilizam-se operadores aritméticos para realizar cálculos.

| Operações        | Símbolos |
| ---------------- | -------- |
| Adição           | +        |
| Subtração        | -        |
| Multiplicação    | \*       |
| Divisão          | /        |
| Resto da divisão | %        |

## 2.2 Operações Relacionais

Verifica-se se um número digitado pelo usuário é positivo ou negativo, ou outra operação de qualquer outra natureza.

| Operações   | Símbolos |
| ----------- | -------- |
| Maior       | >        |
| Maior igual | >=       |
| Menor       | <        |
| Menor igual | <=       |
| Igual       | ==       |
| Diferente   | !=       |

Os operadores relacionais são importantes, pois permitem realizar comparações que terão como resultado um valor lógico (verdadeiro ou falso). Exemplos:

| Operações       | Resultados |
| --------------- | ---------- |
| 3 > 4           | Falso      |
| 5 != 5          | Falso      |
| 16 >= 17 -1     | Verdadeiro |
| 5 + 4 <= 11 - 2 | Verdadeiro |

### _Exercícios Resolvidos_

2. Faça um programa em Portugol WebStudio que realize a verificação de dois números reais. O programa possui como saída a média dos números digitados pelo usuário. Além disso, verifique se a média é maior que 15. O programa tem de possuir a seguinte saída: "A media é: (resultado da média aqui). Ela é maior que 15?"

```
programa
{
	funcao inicio()
	{
        real numero1, numero2, media

        escreva("Digite o valor do número 1: ")
        leia(numero1)

        escreva("Digite o valor do número 2: ")
        leia(numero2)

        media = (numero1 + numero2)/2

        escreva("A média é: ", media, ". Ela é maior que 15? ", media > 15)
	}
}
```

## 3. Desvios condicionais

Trata-se de onde um conjunto de instruções deve ser executado **se** uma condição seja verdadeira. Caso a situação não seja verdadeira, ou seja, **senao**, ele executará uma outra operação. Por exemplo:

### _Exercícios Resolvidos_

3. Faça um programa em Portugol WebStudio que realize a verificação se o usuário é maior de idade. Caso ele seja, a saída deve apresentar a seguinte mensagem: "Maior de idade!" e o valor idade do usuário. Caso contrário, apresentar na saída a mensagem: "Menor de idade!" e o valor referente a idade.

```
programa
{
        funcao inicio()
        {
            inteiro maioridade

            escreva ("Digite uma idade: ")
            leia (maioridade)

            se (maioridade >= 18)
            {
                escreva ("Maior de idade! ", maioridade)
            }
            senao
            {
                escreva ("Menor de idade! ", maioridade)
            }
        }
}
```
