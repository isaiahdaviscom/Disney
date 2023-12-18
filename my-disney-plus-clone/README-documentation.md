## Contents

- [Contents](#contents)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Learn More](#learn-more)
- [Deploy](#deploy)
  - [Netlify](#netlify)
  - [Vercel (optional)](#vercel-optional)
- [Troubleshoot](#troubleshoot)

## Installation

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with Typescript.

Additional Packages

```bash
npm install --save-dev webpack webpack-cli @storybook/react
```

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy

### Netlify

### Vercel (optional)

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Troubleshoot

<details>

  ![Page Not Found](image.png)

  <summary>Page Not Found</summary>
  Netlify indicates a successful deployment, however, the application is not rendering. The default Page Not Found renders.

  Tested Build process locally and was successful in rendering.

  The issue must be in the site configurations for a Netlify.

  ![Alt text](image-1.png)

</details>
