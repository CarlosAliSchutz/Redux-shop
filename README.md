# Redux shop
Primeiro projeto utilizando Redux, aprendendo como criar a primeira action e usar o dispatch para dispará-la e atualizar o estado da aplicação de forma controlada.

## Como rodar o projeto

Instalar as dependências
```bash
npm install
```

Execute a aplicação
```bash
npm start
```
----------------------------

## Fluxo de mudança do estado

No produto da listagem tem um botão pra adicionar ao carrinho

Quando o usuario clicar em adicionar o produto dispara uma action "ADD_PRODUCT_TO_CART"

Essa action vai ser dispachada para o reducer que ouve a action, pega todos os produtos atuais no carrinho e adiciona um novo

O novo estado é uma lista com o produto adicionado, todos os componentes que usam esse estado são atualizados.

## Tecnologias usadas
[![Technologies](https://skillicons.dev/icons?i=js,html,css,react,redux&perline=5)](https://skillicons.dev)
# Redux-shop
