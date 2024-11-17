# Como funciona um projeto em JavaScript

Esse guia é um resumo de como funciona um projeto em JavaScript, mais especificamente usando o framework `Next.js`. Algumas coisas serão mais específicas para o Next.js, mas o foco é dar noções de como funciona um projeto em JavaScript.

## O que é o Next.js?

Next.js é um framework React. Escolhemos usar ele porque ele é popular, tem uma comunidade ativa e tem features que serão úteis para o projeto, como [SSG](https://nextjs.org/docs/app/building-your-application/rendering/server-components#static-rendering-default) (Static Site Generation) que nos permite criar páginas estáticas que não precisam de um servidor, assim reduzindo eventuais custos com o Next.js. E caso se torne necessário um servidor, ele também nos permite criar [SSR](https://nextjs.org/docs/app/building-your-application/rendering/server-components#dynamic-rendering) (Server-Side Rendering).

## Estrutura de arquivos e pastas

![nextjs](assets/images/nextjs-structure.png)

- public/
- src/
  - app/
    - page.tsx
    - layout.tsx
    - sample-page/
      - page.tsx
  - components/
  - lib/
  - types/
  - utils/
- package.json
- tsconfig.json
- next.config.js
- package-lock.json / pnpm-lock.yaml
- .gitignore
- .env
- README.md
- .eslintrc.json
- postcss.config.js
- tailwind.config.js

## Links Úteis

- [Learn Next.js](https://nextjs.org/learn)
- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
