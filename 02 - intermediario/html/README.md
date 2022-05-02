## Conteúdo

- [Uso de H1 até o H6 e Parágrafos](#projeto1)
  - [Exercício](#exercicio1)
- [Lista de Itens Ordenada e Não-Ordenada](#projeto2)
  - [Exercício](#exercicio2)
- [Adicionar Imagens e Vídeos](#projeto3)
  - [Exercício](#exercicio3)
- [Adicionar Links que Abram na Mesma Página e em uma Nova Página](#projeto4)
  - [Exercício](#exercicio4)
- [Formulário](#projeto5)
  - [Exercício](#exercicio5)

---

## Uso de H1 até o H6 e Parágrafos <a name = "projeto1"></a>

Afinal, o que são as tags H do HTML? A tag ```<h1>``` até a ```<h6>``` são conhecidas como elementos de cabeçalho, e possuem seis níveis: H1 sendo o mais importante e o H6 o de menor importância.

Para entender melhor, o Google usa um método de indexação que busca os cabeçalhos que descrevam brevemente os tópicos pesquisados e quanto melhor a utilização dos elementos de cabeçalho, mais alta vai ser sua posição no resultado da pesquisa.

E como utilizar de melhor forma esses elementos cabeçalhos? Devemos considerar a importância dos níveis de cabeçalho, sendo o ```<h1>``` o mais importante e o vai melhorar o resultado em buscadores da internet, deve-se ser usado uma única vez em sua página de web. Já o ```<h2>``` ao ```<h6>```, podem ser utilizados diversas vezes, mas sempre tendo em consciência de suas importâncias de seus níveis.

Agora vamos falar um pouco sobre a tag P. O elemento ```<p>``` representa um parágrafo. Em mídias visuais, os parágrafos são representados como blocos de textos indentados com a primeira letra avançada e separados por linhas em branco. Já no HTML, os parágrafos são utilizados para agrupar conteúdos relacionados de qualquer tipo, como por exemplo: imagens, campos de um formulário e textos.

Podemos ver como utilizar ```<h#>``` e ```<p>``` no exemplo abaixo:

```
<h1>Elementos de cabeçalho</h1>
<h2>Sumário</h2>
<p>Algum texto aqui...</p>

<h2>Exemplos</h2>
<h3>Exemplo 1</h3>
<p>Algum texto aqui...</p>

<h3>Exemplo 2</h3>
<p>Algum texto aqui...</p>

<h2>Veja também</h2>
<p>Algum texto aqui...</p>
```

### Exercício <a name = "exercicio1"></a>

Neste exercício, será proposto as seguintes diretivas:

- Crie um cabeçalho de maior importância para sua pseudo-página;
- Crie três cabeçalhos de menor importância que o anterior para os cabeçalhos das sessões de sua página. Ex.: Perfil, Continue Comprando etc.
- Crie dois cabeçalhos para identificar produtos ou títulos de postagem com um parágrafo abaixo com um breve texto.

---

## Lista de Itens Ordenada e Não-Ordenada <a name = "projeto2"></a>

O elemento HTML ```<ol>``` representa uma lista de itens ordenada, sendo assim, uma lista mostrando uma contagem crescente, podendo ser de variados tipos, como por exemplo: numerais, letras, algarismos romanos ou até mesmo símbolos.

Já o elemento ```<ul>``` representa uma lista não-ordenada, não possuem ordenação numérica a suas posições, seu marcador pode possuir várias formas, como por exemplo: círculos, quadrados, pontos etc.

E para inserirmos itens dentro dessas listas possuímos o elemento ```<li>```, usado para representar itens que fazem parte de uma lista, esse elemento precisa estar presente dentro um elemento pai (```<ol>``` ou ```<ul>```).

Exemplo: 

```
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>
```

### Exercício <a name = "exercicio2"></a>

Nesse exercício, será necessário que você construa:

- Uma lista ordenada de prioridades do estudo da sua semana.
- Uma lista não-ordenada de coisas que você mais gosta de fazer.
- Uma lista ordenada de suas séries ou filmes favoritos com uma lista não-ordenada dentro dela com os personagens favoritos.

---

## Adicionar Imagens e Vídeos <a name = "projeto3"></a>

O elemento HTML ```<img>``` é útilizado para se adicionar imagens a nossas páginas da web. Ele é um elemento vazio (não precisando adicionar tags de fechamento ou conteúdo) que requer ao mínimo um atributo para ser útil. Dessa forma, seu atributo é o ```src``` (source ou em português fonte), esse atributo ```src``` indicará o caminho para a imagem, seja ela armazenada de forma interna (dentro do seu projeto) ou externa (ou em alguma página da web).

O elemento HTML ```<video>``` é utilizado para incorporar conteúdo de vídeo em um documento HTML e como qualquer elemento HTML, este elemento suporta os global attributes.

Já para adicionarmos vídeos aos nossos projetos utilizamos o elemento ```<iframe>```, que representa um contexto de navegação aninhado, efetivamente incorporando outra página HTML para a página atual e possuí vários atributos que podem ser adicionados ao elemento.

Exemplo: 

```
<img src="doguinho.jpg">

<video src="arquivovideo.ogg" autoplay poster="imagemprevia.jpg">
  Desculpa, o seu navegador não suporta vídeos incorporados,
  mas você pode <a href="videofile.ogg">baixá-lo</a>
  e assistir pelo seu reprodutor de mídia favorito!
</video>

<iframe width="560" height="315" src="https://www.youtube.com/embed/gNdl4gNtYww" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```

### Exercício <a name = "exercicio3"></a>

No exercício atual você vai precisar fazer:

- Adicionar uma imagem localmente e uma exeterna;
- Adicionar um vídeo por ```<iframe>``` e alterar o tamanho da tela do vídeo e remover a possibilidade de abrir em tela cheia.

---

## Adicionar Links que Abram na Mesma Página e em uma Nova Página <a name = "projeto4"></a>

O elemento HTML ```<a>``` é conhecido como o elemento âncora, e possuí o atributo ```href``` que tem a função de criar uma hiper-ligação nas páginas de web, arquivos endereços de email etc. O conteúdo de cada ```<a>``` precisará indicar o destino do link.

O elemento ```<a>``` também possui outros atributos, entre eles o atributo ```target```, este atributo tem várias funções que poderão ser usadas como:

- _self: No atual contexto de pesquisa. (Default)
- _blank: Normalmente uma nova aba, porém usuários podem configurar seus navegadores para abrir em uma nova janela.
- _parent: o contexto de navegação pai do atual. Se nenhum pai, se comporta como _self.
- _top: o contexto de navegação mais alto (o contexto "mais alto" que é um ancestral do atual). Se não houver ancestrais, se comporta como _self.

Exemplo: 

```
<a href="carrinho.html" target="_blank">
```

Extra: se você não adicionar o ```_``` antes do ```blank```, o navegador irá abrir uma nova aba, mas se você tentar abrir novamente outro elemento ```<a>``` que esteja sem o ```_``` no atributo ```target```, ele vai continuar carregando a nova página na aba que anteriormente foi aberta, sem criar novas abas de navegação.

### Exercício <a name = "exercicio4"></a>

Nesse exercício:

- Um link que se abra na aba atual;
- Uma imagem com um link que se abra em uma nova aba.

---

## Formulário <a name = "projeto5"></a>

Formulários HTML são um dos principais pontos de interação entre um usuário e um web site ou aplicativo. Eles permitem que os usuários enviem dados para o web site. Na maior parte do tempo, os dados são enviados para o servidor da web, mas a página da web também pode interceptar para usá-los por conta própria.

Todos formulários HTML começam com um elemento ```<form>```. Este elemento define um formulário. É um elemento de container como um elemento ```<div>``` ou ```<p>```, mas ele também suporta alguns atributos específicos para configurar a forma como o formulário se comporta. Todos os seus atributos são opcionais, mas é considerada a melhor prática sempre definir pelo menos o atributo action e o atributo method.

O nosso formulário de contato é muito simples e contém três campos de texto, cada um com uma etiqueta. O campo de entrada para o nome será um campo básico texto de linha única("input"); o campo de entrada do e-mail será um campo de texto com uma única linha("input") que vai aceitar apenas um endereço de e-mail; o campo de entrada para a mensagem será um campo de texto de várias linhas("textarea").

Exemplo:

```
<form action="/pagina-processa-dados-do-form" method="post">
  <div>
    <label for="nome">Nome:</label>
    <input type="text" id="nome" />
  </div>
  <div>
    <label for="email">E-mail:</label>
    <input type="email" id="email" />
  </div>
  <div>
    <label for="msg">Mensagem:</label>
    <textarea id="msg"></textarea>
  </div>
  <button type="submit">Enviar sua mensagem</button>
</form>
```

Alguns elementos podem receber um atributo ```type``` com diversos valores, entre eles os mais frequentes usados são:

- checkbox: Uma caixa de marcação. Você deve usar o atributo value para definir o valor enviado por este item. Use o atributo ```checked``` para indicar se o item está selecionado por padrão. Você também pode usar o atributo ```indeterminate``` para indicar que a caixa de marcação está em um estado indeterminado (na maioria das plataformas, isso desenha uma linha horizontal cortando a caixa).

- date: Um controle para inserir uma data (ano, mês e dia, sem horário).

- email: Um campo para editar um endereço de e-mail. O valor do campo é validado para estar vazio ou ter um único endereço de e-mail válido antes de ser enviado.

- password: Um campo de texto com uma só linha cujo valor é obscurecido. Use o atributo ```maxlength``` para especificar o comprimento máximo do valor que pode ser inserido.

- submit: Um botão que envia o formulário.

- tel: Um controle para inserir um número de telefone; quebras de linha são automaticamente removidas do valor entrado, mas nenhuma outra sintaxe é imposta. Você pode usar atributos como pattern e maxlength para restringir os valores inseridos no controle.

- text: Um campo de texto com uma só linha; quebras de linha são automaticamente removidas do valor entrado.

### Exercício <a name = "exercicio5"></a>

Nesse exercício você precisará:

- Criar um formulário com ```<input>``` que recebam valor de nome, email, idade, dia/mês/ano, telefone e com um marcador de checkbox;
- O formulário precisa conter um botão de envio;
- Um local para adicionar a idade e o dia/mês/ano de nascimento.
- O marcador de checkbox precisa ter no mínimo 5 itens.

---

Informações sobre os elementos são todos das documentações do [MDN Web Docs](https://developer.mozilla.org/).