# Castanha DS — Motion Tokens (explicador interativo)

Explicador interativo dos **motion tokens** do Castanha DS: a cascata `Primitives → Theme → Brand Style → .Motion Styles`, um laboratório de easing e um player dos Motion Styles (Hover In, Pressed, Selected In…). Feito pra motion designers e devs entenderem os tokens vendo eles animar.

**Online:** https://gus-constantino.github.io/castanhads-motion/

## O que tem
- **Motion Styles em ação** — reproduz a transição composta (duração + easing + delay) de cada estilo; toggle Normal/Reduced.
- **Cascata** do estilo, camada por camada (esquerda → direita).
- **Laboratório de easing** — curva cubic-bezier + bolinha no trilho, com slider de duração.
- **Referência** de Duration / Delay (×8) / Easing, clicável.

## Tecnologia
Página única, self-contained (HTML + CSS + vanilla JS, Web Animations API). Sem build, sem dependências. Fontes via Google Fonts. Responsivo, dark-mode e respeita `prefers-reduced-motion`.

## Deploy (GitHub Pages)
Servido como site estático a partir do `index.html` na raiz, branch `main`.
