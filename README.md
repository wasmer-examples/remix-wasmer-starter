This is a [Remix](https://remix.run/) project bootstrapped with `create-remix-app`.

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

You can also run the Remix starter easily using Wasmer (check out the [install guide](https://docs.wasmer.io/install)):

```bash
npm run build
wasmer run . -- --port 3000
```


Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Deploy on Wasmer Edge

The easiest way to deploy your Remix.run app is to use the [Wasmer Edge](https://wasmer.io/products/edge).

Live example: https://remix-wasmer-starter.wasmer.app/

First, you'll need to run `npm run build`, and then, to deploy to Wasmer Edge:

```bash
wasmer deploy
```
