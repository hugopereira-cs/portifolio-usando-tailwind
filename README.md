# Portfólio com Tailwind CSS

Página de portfólio responsiva desenvolvida com HTML5 e Tailwind CSS. O projeto apresenta um layout moderno com navegação lateral adaptativa e seção de apresentação pessoal.

## Visão Geral

Projeto de portfólio de Hugo Pereira, desenvolvedor Front-end e estudante de Ciência da Computação. A página é totalmente responsiva e adapta-se a diferentes tamanhos de tela, incluindo navegação por ícones em dispositivos móveis.

## Estrutura do Projeto

```
.
├── src/
│   ├── index.html          # Página principal do portfólio
│   ├── input.css           # Arquivo CSS de entrada (importa Tailwind)
│   ├── output.css          # Arquivo CSS gerado (compilado pelo Tailwind)
│   ├── img/                # Imagens do projeto (foto de perfil)
│   └── icons/              # Ícones SVG (navegação e redes sociais)
├── tailwind.config.js      # Configuração do Tailwind CSS
├── package.json            # Dependências e metadados do projeto
└── README.md               # Este arquivo
```

## Recursos

- ✅ Design responsivo (mobile, tablet, desktop)
- ✅ Navegação adaptativa (ícones em mobile, menu expandido em desktop)
- ✅ Seção de apresentação com foto de perfil circular
- ✅ Links para redes sociais (LinkedIn, GitHub)
- ✅ Paleta de cores com tons de roxo, amarelo e cinza
- ✅ Animação de pulso no logo

## Requisitos

- Node.js e npm instalados

## Como Executar

1. Instale as dependências:
   ```bash
   npm install
   ```

2. Compile o CSS com Tailwind em modo watch:
   ```bash
   npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
   ```

3. Abra o arquivo `src/index.html` no navegador:
   ```bash
   # Em Linux/macOS
   xdg-open src/index.html  # ou open src/index.html no macOS
   
   # Ou use um servidor local (opcional)
   npx http-server
   ```

## Tecnologias Utilizadas

- **HTML5**: Estrutura e semântica
- **Tailwind CSS** v4.1.18: Framework CSS utilitário
- **SVG**: Ícones vetoriais

## Dependências

- `tailwindcss`: ^4.1.18
- `@tailwindcss/cli`: ^4.1.18
