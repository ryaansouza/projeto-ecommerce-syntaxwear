# SyntaxWear

SyntaxWear é uma landing page para um e-commerce de calçados, projetada para ser moderna, responsiva e visualmente atraente. A página inicial apresenta os produtos de forma organizada e atraente, com seções dedicadas para diferentes categorias e destaques.

## Contexto do Projeto

Este projeto foi desenvolvido como parte de um curso com o objetivo de aplicar e demonstrar habilidades em HTML e CSS. Por ser um projeto de estudo, o foco principal foi no aprendizado e na implementação das tecnologias, e não necessariamente na criação de um produto pronto para o mercado.

## Funcionalidades

- **Hero Section:** Uma grande imagem de banner com um call-to-action para chamar a atenção do usuário.
- **Categorias de Produtos:** Seções que exibem as diferentes categorias de produtos disponíveis (Casual, Esporte, Moderno, Futurista).
- **Grid de Produtos:** Uma grade de produtos em destaque, com imagens e informações sobre os modelos.
- **Design Responsivo:** O layout se adapta a diferentes tamanhos de tela, desde desktops a dispositivos móveis.
- **Navegação Fixa:** O cabeçalho fica fixo no topo da página para facilitar a navegação.

## Tecnologias Utilizadas

- **HTML5:** Para a estrutura e conteúdo da página.
- **CSS3:** Para a estilização e layout, utilizando uma arquitetura de CSS modular e componentizada.
  - **Variáveis CSS:** Para manter a consistência de cores, fontes e outros valores em todo o site.
  - **Reset CSS:** Para garantir uma base de estilos consistente em todos os navegadores.
  - **Componentes:** O CSS é dividido em componentes (header, footer, hero, etc.), facilitando a manutenção e reutilização de estilos.

## Estrutura de Arquivos

O projeto está organizado da seguinte forma:

```
/
├── index.html
├── README.md
├── assets/
│   ├── img/
│   │   ├── banners/
│   │   ├── categories/
│   │   ├── favicons/
│   │   ├── icons/
│   │   ├── logo/
│   │   └── products/
└── css/
    ├── base.css
    ├── reset.css
    ├── variables.css
    └── components/
        ├── footer.css
        ├── header.css
        ├── hero.css
        ├── product-category.css
        └── product-grid.css
```

## Como Utilizar

Para visualizar o site, basta abrir o arquivo `index.html` em qualquer navegador web.

## Customização

- **Conteúdo:** O conteúdo da página pode ser alterado diretamente no arquivo `index.html`.
- **Estilos:** Os estilos podem ser modificados nos arquivos CSS correspondentes. As variáveis de estilo principais estão localizadas em `css/variables.css`.
- **Imagens:** As imagens podem ser substituídas na pasta `assets/img/`.