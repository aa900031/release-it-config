# @aa900031/release-it-config

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]

> My configuration of [release-it](https://github.com/release-it/release-it)

## Features

- [unjs/changelogen](https://github.com/unjs/changelogen) style's changelog
- Support monorepo
- Multiple way to extend: from github, from npm package

## Usage

### From NPM Package (Recommend)

Install this package from npm.

```shell
pnpm add -D @aa900031/release-it-config
```

And use it with **package name** in your release-it configuration file.

> [!NOTE]
> If you are use it in the monorepo, you could use `@aa900031/release-it-config/monorepo`

```json
{
	"extends": "@aa900031/release-it-config"
}
```

### From GitHub

It is easyly to use, but need to install some npm dependencies fist.

```shell
pnpm add -D @release-it/conventional-changelog conventional-changelog-unjs
```

And use it with **github schema** in your release-it configuration file.

> [!NOTE]
> If you are use it in the monorepo, you could use `github:aa900031/release-it-config/monorepo`

```json
{
	"extends": "github:aa900031/release-it-config"
}
```

<!-- Link Resources -->

[npm-version-src]: https://img.shields.io/npm/v/@aa900031/release-it-config?style=flat&colorA=18181B&colorB=F0DB4F
[npm-version-href]: https://npmjs.com/package/@aa900031/release-it-config
[npm-downloads-src]: https://img.shields.io/npm/dm/@aa900031/release-it-config?style=flat&colorA=18181B&colorB=F0DB4F
[npm-downloads-href]: https://npmjs.com/package/@aa900031/release-it-config
