# TAREFAS.md

# Primeira rodada

Como estamos em cinco pessoas, dividi o começo de um jeito que todo mundo consiga trabalhar ao mesmo tempo.

Cada pessoa cria a própria branch, faz sua parte, envia pro GitHub e abre uma Pull Request. Outra pessoa revisa antes do merge.

## Edson

Responsabilidade inicial:


estrutura do header
estrutura do nav
estrutura do footer
integração básica entre as páginas
conferir se o padrão de três colunas está sendo respeitado


Branch:


feature/estrutura-global


Revisão:


Thais Scaramella


## Roberta Alves

Responsabilidade inicial:


index.html
estrutura semântica da Home
organização da coluna central
áreas que depois vão receber os destaques


Branch:


feature/home


Revisão:


Edson


## Aline

Responsabilidade inicial:


produtos.html
estrutura semântica do catálogo
área onde os produtos vão aparecer
espaço preparado para busca e filtros


Branch:


feature/catalogo


Revisão:


Roberta Alves


## Greice - DEV

Responsabilidade inicial:


produto.html
estrutura da página de detalhes
área da imagem
área das informações
espaço para tamanho, quantidade e ações


Branch:


feature/produto


Revisão:


Aline


## Thais Scaramella

Como estamos em cinco, nessa primeira rodada ficam duas páginas menores juntas:


carrinho.html
sobre.html
estrutura do carrinho
área de resumo do pedido
estrutura da página Sobre


Branch:


feature/carrinho-sobre


Revisão:


Greice - DEV


## Ciclo da primeira revisão


Edson revisado por Thais Scaramella
Roberta Alves revisada por Edson
Aline revisada por Roberta Alves
Greice - DEV revisada por Aline
Thais Scaramella revisada por Greice - DEV


## Antes de começar

Primeiro atualiza a `main`:

bash
git switch main
git pull origin main


Depois cria a branch da tarefa.

Exemplo:

bash
git switch -c feature/home


Essa divisão é só a primeira rodada. Depois vamos trocar as responsabilidades pra ninguém ficar preso na mesma página.
