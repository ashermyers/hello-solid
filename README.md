# SolidStart

Everything you need to build a Solid project (With TailwindCSS)

## Creating a project

```bash
# create a new project
git clone https://github.com/ashermyers/hello-solid

# or use github cli
gh repo clone ashermyers/hello-solid
```

## Developing

Once you've created a project and installed dependencies with `yarn` (or `npm install` or `pnpm install`), start a development server:

```bash
yarn dev

# or start the server and open the app in a new browser tab
yarn dev --open
```

## Building

Solid apps are built with _adapters_, which optimise your project for deployment to different environments.

By default, `yarn build` will generate a Node app that you can run with `yarn start`. To use a different adapter, add it to the `devDependencies` in `package.json` and specify in your `vite.config.js`.
