# CAT UI

## Getting Started

### Create a copy of env file

Copy `.env.local.example` to `.env.local`

Update the properties:

Linux: `openssl rand -hex 32` or go to https://generate-secret.now.sh/32

### Install the dependencies

```bash
npm install
# or
yarn
# or
pnpm install
```

### Run the development server

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `src/app/page.tsx`. The page auto-updates as you edit the file.

### Format the files

`pnpm run format:fix`
