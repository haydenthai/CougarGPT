# CougarGPT

This simple chat bot implements Next.js, API Routes, and [OpenAI ChatGPT API](https://beta.openai.com/docs/api-reference/completions/create).

### Components

- Next.js
- OpenAI API (ChatGPT) - streaming
- API Routes (Edge runtime) - streaming

## How to Use

Follow steps below to replicate environment on your own machine

### How to clone 


```bash
git clone https://github.com/haydenthai/CougarGPT.git
```

#### Set up environment variables

Rename [`.env.example`](.env.example) to `.env`:

```bash
cp .env.example .env
```

then, update `OPENAI_API_KEY` with your [OpenAI](https://beta.openai.com/account/api-keys) secret key.

Next, run Next.js in development mode:

```bash
pnpm dev
```

The app should be up and running at http://localhost:3000.
