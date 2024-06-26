# Basic TypeScript project template for Phaser Editor v4.

This is a Phaser Editor 2D v4 project template.

## Configuration

* It includes the latest Phaser v3 runtime as a node package.
* It is coded in TypeScript. The `tsc` is included as a node package.
* It includes a VS Code project configuration (`jsconfig.json` file).

## Compiles the source code

This project is based on TypeScript so to get the game, first, you need to install TypeScript and other dependencies:

```bash
$ npm install
$ npm update
```

Then, for running the game, you need to compile the TypeScript files:

```bash
$ npm run build
```

It outputs the JavaScript code into the `game.js` file.

Often, you would like to run the TypeScript compiler in watch mode:

```bash
$ npm start
```

## Run the editor

* If you have NodeJS installed, you can run the editor using the `editor` NPM script, defined in the `package.json` file:

    ```bash
    $ npm install
    $ npm run editor
    ```

* If you are in a remote environment (like the Gitpod.io IDE), then run the editor like this:

    ```bash
    $ npm run editor-remote
    ```

* If you want to see all the editor options, run:

    ```bash
    $ npx phasereditor2d-launcher -help
    ```

* If Phaser Editor 2D Core is globally installed, you can run:

    ```bash
    $ PhaserEditor2D -project .
    ```