# Projeto: Página sobre o Stomatopoda

Este projeto consiste em uma página web semântica sobre o crustáceo marinho Stomatopoda, desenvolvida como exercício de HTML e CSS.

## Estrutura do Projeto

- `index.html`: Página principal com conteúdo sobre o Stomatopoda.
- `style.css`: Estilos aplicados à página.
- `images/`: Imagens utilizadas no artigo.
- `cypress/`: Testes automatizados com Cypress.
- `.editorconfig`, `.stylelintrc.json`: Configurações de estilo e editor.
- `package.json`: Dependências e scripts do projeto.

## Funcionalidades

- Cabeçalho com título.
- Navegação com links para páginas fictícias.
- Artigo dividido em seções, incluindo tabela, imagens e lista de referências.
- Conteúdo adjacente (aside) com link para vídeo.
- Rodapé com autoria e ano.

## Como executar

1. Instale as dependências:
   ```sh
   npm install
   ```
2. Para rodar os testes:
   ```sh
   npm test
   ```
3. Para abrir o Cypress:
   ```sh
   npm run cypress:open
   ```
4. Para verificar o estilo do CSS:
   ```sh
   npm run lint:styles
   ```

## Testes

Os testes automatizados estão em [`cypress/integration/project.spec.js`](cypress/integration/project.spec.js) e verificam a estrutura semântica da página.
