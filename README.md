This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

O projeto consiste em uma aplicação React com um gerenciador de carrinho de compras usando a Context API. Ele permite que os usuários adicionem itens ao carrinho, removam itens do carrinho e visualizem o preço total dos itens adicionados. O gerenciador de carrinho é implementado através de um componente CartProvider, que fornece um contexto para outros componentes da aplicação acessarem e interagirem com o carrinho. Além disso, a aplicação inclui uma integração com a API do Stripe para processar pagamentos, usando uma API Next.js para criar sessões de checkout. Isso torna possível realizar pagamentos de forma segura e eficiente ao finalizar as compras no carrinho. O projeto oferece uma solução completa e funcional para o gerenciamento de carrinho de compras e processamento de pagamentos em uma aplicação web baseada em React.
 
