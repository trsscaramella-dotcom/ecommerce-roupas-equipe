# ESTRUTURA.md

# Organização inicial do projeto

A ideia dessa estrutura é simples: todo mundo começa do mesmo lugar e sabe onde mexer.

Não tem layout pronto aqui. Só a base.

## Arquivos

ecommerce-roupas-equipe/
├── index.html
├── produtos.html
├── produto.html
├── carrinho.html
├── sobre.html
├── README.md
├── DESIGN.md
├── ESTRUTURA.md
├── PARTICIPANTES.md
├── TAREFAS.md
├── css/
│   ├── global.css
│   ├── layout.css
│   ├── liquid-glass.css
│   └── animations.css
├── js/
│   └── main.js
└── assets/
    ├── imagens/
    │   └── .gitkeep
    └── icons/
        └── .gitkeep


## Estrutura dos HTMLs

Todas as páginas começam mais ou menos assim:

<html>
<header>
  <nav></nav>
</header>

<main>
  <aside></aside>
  <section></section>
  <aside></aside>
</main>

<footer></footer>


Em páginas onde o conteúdo central funciona melhor como conteúdo independente, como `produto.html` e `sobre.html`, usamos `article` no lugar de `section`.

A regra aqui é simples: primeiro escolhemos a tag que faz sentido no HTML. Depois pensamos no CSS.

O Liquid Glass é só o visual. Ele não muda a função semântica do elemento.

## PARTICIPANTES.md

Aqui fica a lista de quem está participando e o ciclo inicial de revisão.

## TAREFAS.md

Aqui ficam as responsabilidades, branches e revisores da rodada atual.

Entrou alguém novo, alguém saiu ou a divisão mudou? Esses dois arquivos precisam ser atualizados.
