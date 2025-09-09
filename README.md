# Next.js Starter Template with shadcn/ui

A minimal Next.js starter template with shadcn/ui components pre-configured.

## Features

- ⚡ Next.js 15 with App Router
- 🎨 Tailwind CSS for styling
- 🧩 shadcn/ui components ready to use
- 📱 Responsive design
- 🌗 Dark mode support
- 📦 TypeScript support
- ✨ ESLint configuration

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

You can start editing the page by modifying `src/app/page.tsx`. The page auto-updates as you edit the file.

## Project Structure

```
├── src/
│   ├── app/                 # App Router pages
│   ├── components/          # React components
│   │   └── ui/             # shadcn/ui components
│   └── lib/                # Utility functions
├── public/                 # Static assets
└── components.json         # shadcn/ui configuration
```

## Adding Components

To add new shadcn/ui components:

```bash
npx shadcn@latest add [component-name]
```

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.
- [shadcn/ui Documentation](https://ui.shadcn.com) - learn about the component library.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
