# TypeScript project

This is a starter TypeScript project with minimal configuration.

## Required tools

- [Visual Studio Code](https://code.visualstudio.com) - popular source code editor with a lot of plugins
- [Node.js](https://nodejs.org) - JavaScript interpreter for running JavaScript code on server

## Configuration

TypeScript compiler is configured to compile all *.ts* files inside **src** folder. Compiled *.js* files are in **dist** folder.

Target JavaScript specification is **Ecma 5**.

```json
{
  "compilerOptions": {
    "target": "es5",
    "module": "commonjs",
    "declaration": true,
    "sourceMap": true,
    "outDir": "dist",
    "strict": true
  },
  "include": ["src/**/*"]
}
```

### How to compile

```shell
> tsc
```

### How to run

```shell
> node .\dist\startup.js
```
