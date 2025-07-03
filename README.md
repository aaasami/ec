## Connect the frontend to Supabase

## Install Supabase Client Library
Run this command in your frontend project:

- `npm install @supabase/supabase-js`

## Supabase Client
You already have one on lib/supabaseClient.js

## Set Up Environment Variables
create a .env.local file:
- `NEXT_PUBLIC_SUPABASE_URL=your-supabase-project-url`
- `NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key`

--Replace your-supabase-project-url and your-supabase-anon-key with values from your Supabase dashboard:

Go to Settings → Data API
Copy the Project URL

Go to Settings → API keys
Copy the anon public key

If you don't know the supabase account and password, please the Supabase Team(Discord) chat history.

⚠ Do not commit .env.local to version control (e.g. GitHub).

## Run Your Frontend
Start your development server:

- `npm run dev`

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
