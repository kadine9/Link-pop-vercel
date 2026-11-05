# Link Nest For Later

Create this with database for storing links

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://link-nest-for-later.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/02bcf42f-d741-4004-a68e-3cdaf7179a7d).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```

## Deploying to Vercel

This application is built with **TanStack Start** and **Nitro**. It is pre-configured with `vercel.json` and a Vercel-optimized Nitro preset.

### Option 1: Deploy via Vercel Dashboard (Git)

1. Push your repository to GitHub, GitLab, or Bitbucket.
2. Go to [vercel.com/new](https://vercel.com/new) and import the repository.
3. Vercel automatically detects the framework via `vercel.json`.
4. Under **Environment Variables**, add the required keys:
   - `SUPABASE_URL`
   - `SUPABASE_PUBLISHABLE_KEY`
   - `SUPABASE_SERVICE_ROLE_KEY`
   - `VITE_SUPABASE_URL`
   - `VITE_SUPABASE_PUBLISHABLE_KEY`
5. Click **Deploy**.

### Option 2: Deploy via Vercel CLI

Run the following command from your terminal:

```sh
npx vercel
```

Follow the CLI prompts to link or create the project. For a production deployment:

```sh
npx vercel --prod
```
