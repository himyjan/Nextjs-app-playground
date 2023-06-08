# Next.js App Router + Turbopack Playground

[Turbopack](https://turbo.build/pack) is a new incremental bundler optimized for JavaScript and TypeScript, written in Rust by the creators of Webpack and Next.js at [Vercel](https://vercel.com). On large applications Turbopack updates 10x faster than Vite and 700x faster than Webpack ([benchmark](https://turbo.build/pack/docs/benchmarks)). For the biggest applications the difference grows even more stark with updates up to 20x faster than Vite.

This playground is a mirror of the [Next.js v13 App Directory Playground](https://github.com/vercel/app-playground), but uses Turbopack as the Next.js development server (`next dev --turbo`).

**As a reminder, Turbopack is currently in alpha and not yet ready for production. We appreciate your ongoing support as we work to make it ready for everyone.**

Next.js introduced the App Router. This is the result of the [Layouts RFC](https://nextjs.org/blog/layouts-rfc) previously published for community feedback. This includes support for:

- **Layouts:** Easily share UI while preserving state and avoiding re-renders.
- **Server Components:** Making server-first the default for the most dynamic applications.
- **Streaming:** Display instant loading states and stream in updates.
- **Suspense for Data Fetching:** `async`/`await` support and the `use` hook for component-level fetching.

The App Router can coexist with the existing `pages` directory for incremental adoption. While you **don't need to use the App Router** when upgrading to Next.js 13, we're laying the foundations to build complex interfaces while shipping less JavaScript.

## Running Locally

1. Install dependencies:

```sh
pnpm install
```

2. Start the dev server:

```sh
pnpm dev
```

## Documentation

https://nextjs.link/with-turbopack

https://beta.nextjs.org/docs

## Leave Feedback

https://nextjs.link/turbopack-feedback

https://github.com/vercel/next.js/discussions/41745
