# @aa900031/release-it-config

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
