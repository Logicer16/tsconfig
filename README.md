# Logicer's Typescript Base Configuration

[![npm (scoped)](https://img.shields.io/npm/v/%40logicer/tsconfig)](https://www.npmjs.com/package/@logicer/tsconfig)
[![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/m/Logicer16/tsconfig)](https://github.com/Logicer16/tsconfig/graphs/contributors)

Logicer's Typescript configuration for use in other projects. Designed to be built upon for the project's specific needs.

## Install

```sh
npm install --save-dev typescript @logicer/tsconfig
```

## Usage

In the project's `tsconfig.json`:

```
{
  "extends": "@logicer/prettier-config",
  ... // Your modifications
  "compilerOptions": {
		"outDir": "<out-directory>" // defaults to "./dist"
	},
  "include": [
    "<source-directory>" // defaults to "./src/**/*"
  ]
}
```
