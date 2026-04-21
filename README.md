# quizpdf

Upload a PDF — a course, a paper, a manual — and the app generates an interactive quiz from its contents. Built on the Vercel AI SDK with provider-agnostic model support: Google Gemini, Anthropic Claude, or OpenAI GPT.

## Run locally

```bash
git clone https://github.com/zay168/quizpdf.git
cd quizpdf
npm install
cp .env.example .env   # add GOOGLE_API_KEY, ANTHROPIC_API_KEY, OPENAI_API_KEY
npm run dev
```

## Deploy

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fzay168%2Fquizpdf)

## Stack

Next.js 15 (App Router) · Vercel AI SDK 4 · TailwindCSS · Radix UI · Framer Motion
