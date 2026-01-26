# Projeto Final do Curso de Tailwind da DIO

Este é um projeto desenvolvido durante um curso de Tailwind CSS. O objetivo do projeto é criar uma página de portfólio simples e responsiva.

## Visão Geral

O projeto consiste em uma única página HTML (`index.html`) que é estilizada com Tailwind CSS. A página é um portfólio e inclui uma breve biografia e links para minhas redes sociais.

## Estrutura do Projeto

- `src/index.html`: O arquivo HTML principal.
- `src/input.css`: O arquivo CSS de entrada para o Tailwind CSS.
- `src/output.css`: O arquivo CSS de saída gerado pelo Tailwind CSS.
- `src/img/`: Contém as imagens usadas no projeto.
- `src/icons/`: Contém os ícones SVG usados no projeto.
- `tailwind.config.js`: O arquivo de configuração do Tailwind CSS.
- `package.json`: O arquivo de manifesto do projeto, que inclui as dependências.

## Como Executar o Projeto

1.  Clone o repositório:
    ```bash
    git clone <url-do-repositorio>
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd projeto-curso-tailwind
    ```
3.  Instale as dependências:
    ```bash
    npm install
    ```
4.  Execute o script para compilar o CSS com o Tailwind:
    ```bash
    npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
    ```
5.  Abra o arquivo `src/index.html` em seu navegador.

## Tecnologias Utilizadas

- HTML5
- Tailwind CSS
