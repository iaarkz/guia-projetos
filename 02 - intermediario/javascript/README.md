## Conteúdo

- [Calculadora](#calculadora)
- [Requisitos](#requisitos)
- [Bônus](#bonus)
- [Exemplos](#exemplos)
- [Explicações extras](#extra)

---

## Calculadora <a name = "calculadora"></a>

As calculadoras não são apenas uma das ferramentas mais úteis disponíveis, mas também são uma ótima maneira de entender a interface do usuário e o processamento de eventos em um aplicativo. Neste problema, você criará uma calculadora que suporta cálculos aritméticos básicos com números inteiros.

O estilo é com você, então use sua imaginação e seja criativo! Você também pode achar que vale a pena experimentar o aplicativo de calculadora em seu dispositivo móvel para entender melhor a funcionalidade básica e os casos extremos.

<img src="https://i.ibb.co/YQ4S0hX/Screenshot-79.png" style="width: 50%; margin-left: 50; transform: translateX(50%)">

Com base nas últimas aulas de JavaScript ([Switch Case](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/switch) e [If e Else](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/if...else)), vamos construir uma calculadora utilizando os arquivos `index.html` e `style.css` que já estão na pasta do projeto (caso você queira, pode construir a sua própria do zero), poderá ser necessário adicionar `ids` e/ou `classes` ao `index.html`, e construir a lógica utilizando o JavaScript para que ela funcione.

### Requisitos <a name = "requisitos"></a>

➡️ O usuário pode ver um display mostrando o número atual inserido ou o resultado da última operação.

➡️ O usuário pode ver um teclado de entrada contendo botões para os dígitos `0-9`, operações `+`, `-`, `/` e `=`, um botão `C` (para limpar) e um botão `AC` (para limpar tudo).

➡️ O usuário pode inserir números como sequências de até `8` dígitos clicando nos dígitos no teclado de entrada. A entrada de qualquer dígito maior que `8` será ignorada.

➡️O usuário pode clicar em um botão de operação para exibir o resultado dessa operação em:

- o resultado da operação anterior e o último número inserido OU
- os dois últimos números inseridos OU
- o último número digitado

➡️ O usuário pode clicar no botão `C` para limpar o último número ou a última operação. Se a última entrada do usuário foi uma operação, o display será atualizado para o valor que o precedeu.

➡️ O usuário pode clicar no botão `AC` para limpar todas as áreas de trabalho internas e definir a exibição para `0`.

➡️ O usuário pode ver `ERR` exibido se qualquer operação exceder o máximo de `8` dígitos.

### Bônus <a name = "bonus"></a>

➡️ O usuário pode clicar em um botão `±` para alterar o sinal do número exibido no momento.

➡️ O usuário pode ver um botão de ponto decimal `.` no teclado de entrada que permite que números de ponto flutuante de até 3 casas sejam inseridos e operações sejam realizadas até o número máximo de casas decimais inseridas para qualquer número.

### Exemplos <a name = "exemplos"></a>

[Calculator javascript](https://codepen.io/lennon/pen/mVmpEQ)

[BHMBS - JS-Neumorphic-Calculator](https://barhouum7.github.io/JS-Neumorphic-Calc.github.io/)

[Javascript iOS Style Calculator](https://codepen.io/ssmkhrj/full/jOWBQqO)

[Javascript Calculator](https://codepen.io/giana/pen/GJMBEv)

[Javascript-CALC](https://github.com/0xAndre/javascript-calc)

### Explicações extras: <a name = "extra"></a>

Você não precisa completar todos os requisitos, o importante é a calculadora estar funcional após o final do desafio. Os arquivos `index.html` e `style.css` trarão o que queremos como base para que a calculadora seja construída, porém se quiser se desafiar, podem criar uma calculadora com todos os requisitos pedidos e os bônus.
