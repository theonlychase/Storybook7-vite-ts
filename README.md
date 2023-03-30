# Storybook 7 - Vite/Vue3/Typescript

Storybook 7 is compatible with Node LTS (18.15.0).

## Webstorm
1. Verify Node interpreter is set to Node LTS (18.15.0)
2. Verify Node Package Manager is set to Yarn (3.5.0)
3. Correct versions are pinned in package.json under volta

If you run into any issues on install, try running the storybook automigrate tool:

```sh
npx storybook@next automigrate
```

## Project Setup

### Install dependencies
```sh
yarn
```

### Compile and Hot-Reload for Development

```sh
yarn storybook
```

### Type-Check, Compile and Minify for Production

```sh
yarn build-storybook
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
yarn test:unit
```

### Lint with [ESLint](https://eslint.org/)

```sh
yarn lint
```
