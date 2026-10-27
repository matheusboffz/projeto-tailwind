# Vértice Motors

Landing page demonstrativa para uma concessionária fictícia de carros novos e seminovos. O projeto apresenta um catálogo de veículos, opções de financiamento e informações para ajudar visitantes a conhecer a loja.

## Recursos da página

- Layout responsivo para diferentes tamanhos de tela.
- Seção principal com chamadas para o catálogo e contato.
- Formulário visual para busca por categoria, faixa de preço e ano.
- Catálogo com seis veículos de exemplo.
- Seções de diferenciais, depoimentos e contato.
- Ilustrações dos veículos feitas em SVG.

## Tecnologias

- HTML5
- Tailwind CSS via CDN, com cores e fontes personalizadas no próprio HTML.
- CSS puro com organização BEM em `style.css`.
- Fontes DM Sans e Sora, carregadas do Google Fonts.

## Como visualizar

Não é necessário instalar dependências nem executar um processo de build.

1. Clone ou baixe este repositório.
2. Abra `index.html` diretamente no navegador. Se preferir, use uma extensão como Live Server no VS Code.

O Tailwind CSS e as fontes são carregados de serviços externos, então é necessária uma conexão com a internet para que todos os estilos e fontes apareçam corretamente.

## Arquivos

- `index.html`: página demonstrativa estilizada com Tailwind CSS.
- `style.css`: folha de estilos alternativa em CSS puro, com classes organizadas pela metodologia BEM.

O HTML atual usa Tailwind CSS pelo CDN e não importa `style.css`; os dois arquivos representam abordagens de estilo distintas para o projeto.

## Observação

Esta é uma interface estática para fins demonstrativos. A busca, os filtros e os links de contato não estão conectados a um catálogo, serviço ou backend.
