# Portugol

## Introdução à Programação

No [Portugol WebStudio](https://portugol-webstudio.cubos.io/ide) a priori temos a entrada e saídas de dados. A entrada de dados permite que o usuário pode digitar números, palavras, frases, entre outros. Já saída de dados permite ao algoritmo exibir dados na tela do computador.

O comando para entrada de dados é:

```
 leia (nome_da_variavel)
```

O comando para saída de dados é:

```
escreva("Escreva o texto a ser digitado")
```

## Declarações de variáveis

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

- logico: Declara a variável para exibir se determinada condição é verdadeira ou falsa. Exemplo:

```
logico 3<4
```

- const: Declara a variável a um valor de constante. Tal valor de variável **não** pode ser alterado até o final do código.

```
const real PI = 3.1415926535
```

## Operações Matemáticas

Utilizam-se operadores aritméticos para realizar cálculos.

| Operações        | Símbolos |
| ---------------- | -------- |
| Adição           | +        |
| Subtração        | -        |
| Multiplicação    | \*       |
| Divisão          | /        |
| Resto da divisão | %        |

## Operações Relacionais

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
