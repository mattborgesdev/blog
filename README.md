# mattborgesdev.github.io
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Github Pages](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white)

Este repositório contém o código-fonte do meu portfólio pessoal, desenvolvido com [Next.js](https://nextjs.org/).

## Tecnologias Utilizadas

- [Next.js](https://nextjs.org/) — Framework React para sites rápidos e modernos.
- [TypeScript](https://www.typescriptlang.org/) — JavaScript com tipagem estática.
- [Tailwind CSS](https://tailwindcss.com/) — Utilitários CSS para estilização ágil.
- [next/font](https://nextjs.org/docs/basic-features/font-optimization) — Otimização de fontes web.
- [GitHub Pages](https://pages.github.com/) — Hospedagem gratuita para sites estáticos.

## Como rodar localmente

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/mattborgesdev/mattborgesdev.github.io.git
cd mattborgesdev.github.io
npm install
```

Inicie o servidor de desenvolvimento:

```bash
npm run dev
# ou
yarn dev
# ou
pnpm dev
# ou
bun dev
```

Acesse [http://localhost:3000](http://localhost:3000) no navegador para visualizar o site.

## Estrutura do Projeto

- `src/app/` — Páginas e componentes principais do site.
- `public/` — Imagens e arquivos estáticos.
- `src/components/` — Componentes reutilizáveis.
- `src/app/globals.css` — Estilos globais.
- `tailwind.config.ts` — Configuração do Tailwind CSS.

## Deploy

O deploy é realizado automaticamente no [GitHub Pages](https://pages.github.com/) sempre que há um push na branch principal. O projeto está configurado para exportação estática e publicação automática. No entanto, existe uma limitação relacionada ao DNS: após cada deploy, é necessário reconfigurar o domínio personalizado em Settings > Code and Automation > Pages > Custom domain.

## Contribuição

Sinta-se à vontade para abrir issues ou pull requests com sugestões de melhorias ou correções.

## Saiba Mais

- [Documentação Next.js](https://nextjs.org/docs)
- [Meu LinkedIn](https://www.linkedin.com/in/mattborgesdev/)
- [Portfólio Online](https://mattborgesdev.github.io/)
