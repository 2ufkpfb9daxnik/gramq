# gramq

[vercelに上げています](https://vercel.app/gramq)

新配列を手動で作るときに使うn-gram頻度検索サービスです。

検索窓に入れるとフィルタが掛かったうえでの検索結果を返します。

過去自分が配列を作っているときにあると嬉しいなと思ったので作りました。もう今は完成していてあんまり意味ないんですが、いまでもふとした時に気になるのでそういうときのためにあります。

## 開発

reactとnext.js、tailwindcssを使っています。データは下処理して/data以下に生jsonで保存してあります。

2025/04/28の朝に思い立って作りました。

github copilotでclaude 3.7 sonnetを使いながら作りました。githubには最終的なデータしか上げていないのでありませんが、下処理には今一番意味がわかるのでpythonを使いました。

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

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

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
