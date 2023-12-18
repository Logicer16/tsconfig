# Logicer's Typescript Base Configuration

[![npm (scoped)](https://img.shields.io/npm/v/%40logicer/tsconfig)](https://www.npmjs.com/package/@logicer/tsconfig)
[![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/m/Logicer16/tsconfig)](https://github.com/Logicer16/tsconfig/graphs/contributors)

Logicer's Typescript configuration for use in other projects. Designed to be built upon for the project's specific needs. Includes the type-coverage plugin.

## Install

```sh
npm install --save-dev typescript ts-plugin-type-coverage @logicer/tsconfig
```

## Usage

In the project's `tsconfig.json`:

```
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "extends": "@logicer/prettier-config",
  ... // Your modifications
  "compilerOptions": {
		"outDir": "<out-directory>"
	},
  "include": [
    "<source-directory>"
  ]
}
```
