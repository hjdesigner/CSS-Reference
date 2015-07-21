## O QUE É PSEUDO-CLASS

As pseudo-classes são muito úteis para fazermos manipulações estruturais, ou alterações de estilos de forma dinâmica.

Dentro do pseudo-class pode ser usado para inserir praticamente qualquer tipo de conteudo:

* Uma imagem, por exemplo ou icone
* Uma string tipo texto 
* tambem conta com uma string Escaping de Unicode e torna um personagem

## Suporte
Você provavelmente irá se deparar (ou ja se deparou ) anotações : depois que utiliza um dos dois pontos em vez de dois.

Em css1 e css2, pseudo-class foram definidos para comçar com um dois pontos (:), assim com pseudo-class (por exemplo: hover). Em css3, a anotação de pontos (::) foi introduzidos para pseudo-class, a fim de diferenciá-las das pseudo-classes.

Todos os navegadores que suportam a notação de dois cólon também suporta a notação de um. IE 8, no entanto não suporta a notação de dois pontos.

## Acessibilidade
Conteúdo adicionado utilizando pseudo-elementos não está inserido no DOM e é exibido apenas visualmente. Assim os leitores de tela não será capas de acessar e ler o conteúdo gerado. Portanto é recomendavel que você não usar em conteúdo vital em uma pagina.