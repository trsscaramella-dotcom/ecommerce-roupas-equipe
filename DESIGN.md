# DESIGN.md

# Direção visual do projeto

Esse arquivo serve só pra gente não acabar criando cinco sites diferentes dentro do mesmo projeto.

Ainda não tem design pronto. Aqui ficam apenas as decisões que todo mundo precisa seguir quando começar a mexer no CSS.

## Layout

A estrutura combinada é essa:


HEADER ocupando toda a largura

COLUNA ESQUERDA | COLUNA CENTRAL | COLUNA DIREITA

FOOTER ocupando toda a largura


No desktop teremos três colunas.

A ideia é montar isso com CSS Grid, mas o código vai ser feito pela equipe durante as tarefas.

## Liquid Glass

O padrão visual será Liquid Glass.

Ele deve aparecer principalmente em:


cards
menus
botões
inputs
painéis
modais


O efeito ainda não está feito.

No arquivo abaixo deixei algumas pistas do que pesquisar e testar:


css/liquid-glass.css


A gente vai trabalhar com transparência, blur, bordas claras, sombras, profundidade, reflexos, gradientes e animações.

O importante é manter o mesmo padrão. Se cada pessoa fizer um vidro totalmente diferente, o site vai ficar estranho.

## Responsividade

No desktop teremos as três colunas.

No tablet e no celular a equipe vai decidir a melhor forma de reorganizar o conteúdo.

Não precisa decidir tudo agora. Quando chegar nessa parte, a gente testa e ajusta junto.
