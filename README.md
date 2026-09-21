# Castanha DS — Motion Tokens (explicador interativo)

Explicador interativo dos **motion tokens** do Castanha DS: a cascata `Primitives → Theme → Brand Style → .Motion Styles`, um laboratório de easing e um player dos Motion Styles (Hover In, Pressed, Selected In…). Feito para motion designers e devs entenderem os tokens acompanhando cada um em movimento.

**Online:** https://gus-constantino.github.io/castanhads-motion/

## O que tem
- **Motion Styles em ação** — hover, press e teclado no próprio botão disparam o estilo correspondente, e o painel de tokens acompanha. O checkbox do Castanha DS responde a Selected In/Out.
- **Cascata** do estilo, camada por camada (esquerda → direita).
- **Laboratório de easing** — curva cubic-bezier + bolinha no trilho, com slider de duração.
- **Referência** de Duration / Delay (×8) / Easing, clicável.

## Tecnologia
Página única, self-contained (HTML + CSS + vanilla JS). Sem build, sem dependências. O demo usa CSS transitions, para que hover e press componham em vez de um sobrescrever o outro; a bolinha do laboratório usa Web Animations API. Fontes via Google Fonts. Responsivo, com tema light por padrão e dark por escolha no botão.

O checkbox é um **port** do componente de `castanha-react` — mesma estrutura, mesmos class names e valores de token do `castanha-tokens`. Não é o componente React, porque a página não tem build nem dependências.

## Pendências
- Modo **Reduced** desabilitado até o token ser publicado no Figma.
- A página **não** lê `prefers-reduced-motion`; a escolha de tema e de modo é manual.

## Deploy (GitHub Pages)
Servido como site estático a partir do `index.html` na raiz, branch `main`.
