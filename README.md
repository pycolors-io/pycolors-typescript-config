![npm](https://img.shields.io/npm/v/@pycolors/typescript-config)
![license](https://img.shields.io/npm/l/@pycolors/typescript-config)

# @pycolors/typescript-config

Production-ready TypeScript `tsconfig` presets for modern web apps and
libraries.

Built to keep PyColors projects consistent (UI, Tokens, Starters,
Marketing) without re-inventing compiler options in every repo.

------------------------------------------------------------------------

## ⚠️ Read-only mirror

This repository is automatically synced from the **PyColors monorepo**.\
**Source of truth:**
https://github.com/pycolors-io/pycolors/tree/main/packages/typescript-config

You can safely open Issues in this repository.\
The source code lives in the private PyColors monorepo and changes are
synced here automatically.

------------------------------------------------------------------------

## Install

``` bash
pnpm add -D @pycolors/typescript-config
# or
npm i -D @pycolors/typescript-config
```

------------------------------------------------------------------------

## Usage

### Base (Node / libraries)

`tsconfig.json`:

``` json
{
  "extends": "@pycolors/typescript-config/base"
}
```

### Next.js (App Router / Pages Router)

`tsconfig.json`:

``` json
{
  "extends": "@pycolors/typescript-config/nextjs"
}
```

### React library

`tsconfig.json`:

``` json
{
  "extends": "@pycolors/typescript-config/react-library"
}
```

------------------------------------------------------------------------

## What's included

-   **base** — strict modern defaults (ES2022 + DOM), NodeNext
    resolution
-   **nextjs** — Next plugin + Bundler resolution + `noEmit`
-   **react-library** — React JSX runtime for libraries

------------------------------------------------------------------------

## License

MIT
