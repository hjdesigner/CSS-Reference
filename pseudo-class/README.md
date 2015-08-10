## O QUE É PSEUDO-CLASS

As pseudo-class são muito úteis para fazermos manipulações estruturais, ou alterações de estilos de forma dinâmica.

Dentro do pseudo-class pode ser usado para inserir praticamente qualquer tipo de conteudo:

* Uma imagem, por exemplo ou icone
* Uma string tipo texto 
* Também conta com uma string Escaping de Unicode e torna um personagem

## Suporte
Você provavelmente irá se deparar (ou ja se deparou ) anotações : depois que utiliza um dos dois pontos em vez de dois.

Em css1 e css2, pseudo-class foram definidos para comçar com um dois pontos (:), assim com pseudo-class (por exemplo: hover). Em css3, a anotação de pontos (::) foi introduzidos para pseudo-class, a fim de diferenciá-las das pseudo-classes.

Todos os navegadores que suportam a notação de dois cólon também suporta a notação de um. IE 8, no entanto não suporta a notação de dois pontos.

## Acessibilidade
Conteúdo adicionado utilizando pseudo-elementos não está inserido no DOM e é exibido apenas visualmente. Assim os leitores de tela não será capas de acessar e ler o conteúdo gerado. Portanto é recomendavel que você não user em conteúdo vital em uma pagina.

Videos prontos no canal [COISA DE DEV](https://www.youtube.com/channel/UC4W-b9Q1I0mzGGzFKOu-66g):

* Utilizando a propriedade ::after para colocar um elemento após o conteúdo. [Clique aqui](https://www.youtube.com/watch?v=--x7AZJXv58)

* Utilizando a propriedade ::before para colocar um elemento antes do conteúdo. [Clique aqui](https://www.youtube.com/watch?v=FXnYgUhUkxk)

* Utilizando a propriedade ::First-letter e ::First-Line para estilizar a primeira letra e a primeira linha do paragrafo. [Clique aqui](https://www.youtube.com/watch?v=GvXczaBBGaM)