# Example app with [chakra-ui](https://github.com/chakra-ui/chakra-ui) and TypeScript

It also utilizes prettier, eslint, and husky for formatting commits.

### Using `create-next-app`

Follow the steps below for a basic version of this starter template.

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init), [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/), or [pnpm](https://pnpm.io) to bootstrap the example:

```bash
npx create-next-app --example with-chakra-ui with-chakra-ui-app
```

```bash
yarn create next-app --example with-chakra-ui with-chakra-ui-app
```

```bash
pnpm create next-app --example with-chakra-ui with-chakra-ui-app
```

Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).

## Notes

Chakra has supported Gradients and RTL in `v1.1`. To utilize RTL, [add RTL direction and swap](https://chakra-ui.com/docs/features/rtl-support).

If you don't have multi-direction app, you should make `<Html lang="ar" dir="rtl">` inside `_document.ts`.
