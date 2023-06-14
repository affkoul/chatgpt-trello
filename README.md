# ChatGPT Prompted and Assisted Trello
ChatGPT Prompted and Assisted Trello Clone Web App

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run npm i -S, to install all required dependencies:

```bash
npm i -S
```

Next, run npm run dev, to start the front-end:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Back-End

This app uses cloud.appwrite.io for back-end services.

Follow the youtube tutorial below from "56:10 Implementing Appwrite Cloud" to the end of "1:06:31 Implementing the Appwrite Cloud Database" to set up your back-end.

[Let’s build TRELLO 2.0 with REACT! (Next.js 13.4, GPT-4, Drag & Drop, Zustand, Appwrite Cloud, TS)](https://www.youtube.com/live/TI2AvfCj5oM?feature=share) 

Note: the information needed for the configuration in the .env file will be found in your "cloud.appwrite.io" once you complete the step above.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Deploy on own server

First, modify the file next.config.js with the correct base path where you plan to deploy the app.

Next, push all the code in this repository to the directory above.

Then, follow the steps under the section "Getting Started" to install all needed dependencies, or not at all, since we are docker-containerizing the app.

Now, run COMPOSE_DOCKER_CLI_BUILD=1 DOCKER_BUILDKIT=1 docker-compose build to build the container image.

```bash
COMPOSE_DOCKER_CLI_BUILD=1 DOCKER_BUILDKIT=1 docker-compose
```

To finish, run docker-compose up to get the app running on your server.

```bash
docker-compose up
```

Bonus: 

Follow the youtube tutorial below from "24:08 till the end for support on how to get users access your app without having to type in the port number, just like every production app should work.

[How to Deploy a Next.js Application on a VPS Server - Next.js + Headless WordPress [ part 15]](https://youtu.be/kHL1FGg0XDA) 

![GAC Logo](https://geniusandcourage.com/favicon.ico)

ChatGPT Prompted and Assisted Trello Web App By [GAC DEV](https://geniusandcourage.com)

## In Action

![ChatGPT Prompted and Assisted Trello Web App](https://hlwsdtech.com:8081/images/chatgpt-trello.png)

