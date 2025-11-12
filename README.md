# Next.js Demo

A React full-stack application demo project based on [Next.js](https://nextjs.org/) 16. Demonstrates how to build modern Web applications using Next.js App Router, TypeScript, and Tailwind CSS.

## Tech Stack

- **Next.js**: 16.0.0
- **React**: 19.2.0
- **TypeScript**: 5.x
- **Tailwind CSS**: 4.x
- **ESLint**: 9.x

## Project Structure

```
nextjs-demo/
├── app/
│   ├── layout.tsx        # Root layout component
│   ├── page.tsx          # Home page
│   ├── globals.css       # Global styles
│   └── favicon.ico       # Website icon
├── public/               # Static assets
│   ├── next.svg
│   ├── vercel.svg
│   └── ...
├── next.config.ts        # Next.js configuration
├── tsconfig.json         # TypeScript configuration
├── postcss.config.mjs    # PostCSS configuration
├── eslint.config.mjs     # ESLint configuration
└── README.md
```

## Features

- App Router architecture
- Server-Side Rendering (SSR)
- Static Site Generation (SSG)
- Automatic code splitting
- Image optimization
- Dark mode support
- TypeScript support
- Tailwind CSS styling

## Quick Start

### Prerequisites

- Node.js 18 or higher
- npm, yarn, or pnpm

### Installation and Running

```bash
# Install dependencies
npm install
# Or
yarn install
# Or
pnpm install

# Run development server
npm run dev
# Or
yarn dev
# Or
pnpm dev
```

The application will start at `http://localhost:3000`.

### Build and Deploy

```bash
# Build production version
npm run build

# Start production server
npm start

# Run Lint
npm run lint
```

## Project Features

### App Router

Uses Next.js 13+ App Router, providing:
- File-system-based routing
- Layouts and templates
- Loading states
- Error handling
- Route groups and parallel routes

### Page Structure

- **`app/layout.tsx`**: Root layout containing shared UI for all pages
- **`app/page.tsx`**: Home page component
- **`app/globals.css`**: Global styles file

### Styling System

Uses Tailwind CSS 4.x for styling:
- Utility-first CSS framework
- Dark mode support
- Responsive design
- JIT compilation

## Development

### Hot Reload

Next.js provides fast refresh functionality that automatically updates the browser when code is modified.

### TypeScript

Project fully uses TypeScript for type safety:
- Strict type checking
- Auto-completion and IntelliSense
- Compile-time error detection

### Code Quality

- **ESLint**: Code linting
- **TypeScript**: Type checking
- **Prettier**: Code formatting (if configured)

## Deployment

### Vercel (Recommended)

Next.js is created by Vercel and can be deployed with one click:

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

### Other Platforms

Next.js can be deployed to any platform supporting Node.js:
- Docker
- AWS
- Google Cloud
- Azure
- Self-hosted servers

## References

- [Next.js Documentation](https://nextjs.org/docs)
- [Next.js Learn](https://nextjs.org/learn)
- [Next.js GitHub](https://github.com/vercel/next.js)
- [Vercel Deployment](https://vercel.com/new)
