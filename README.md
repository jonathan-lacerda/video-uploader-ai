<h1 align="center">
  Video Uploader AI
</h1>

## 💻 Project

🚧 Application in which the user uploads videos and, through AI, automatically creates eye-catching titles and descriptions with good indexing according to the content presented in the video. 🚀🚀

## ✨ Technologies

Front:

- [x] Vite
- [x] React
- [x] Tailwind
- [x] RadixUI
- [x] Shadcn/UI
- [x] WebAssembly

Back:

- [x] Prisma
- [x] Fastify
- [x] OpenAI

## 🏃‍♂️ Running the project

Clone the repository, then follow the steps indicated

Use **npm install** or **yarn** to install project dependencies.

In both the web project and the api project, run the command to install the dependencies:

```cl
yarn
```

Then, in the root of the **API project**, run the following command to create the default prompt templates in Prisma:

```cl
npx prisma db seed
```

Then, still at the root of the **api project**, run the command below to start the server:

```cl
yarn dev
```

Once this is done, go to the root of the **web project** and run the command below to start the application:

```cl
yarn dev
```

## 🚨 Attention

To work, you need to have these two keys in your **.env** file in the root of the **api project**, you need to have a connection key with the openai API to use the AI

```cl
DATABASE_URL="file:./dev.db"
OPENAI_KEY="your-openai-key"
```
