# Electron TypeScript Quick Start

> This template is based on the official [electron-quick-start](https://github.com/electron/electron-quick-start) repository (but with typescript + electron-builder)

> Note: checkout `prettier` branch for a project with prettier/tslint integration + git hooks for enforcing consistent styling

## How to use?

```sh
# install dependencies
$ npm install

# compile typescript files
$ npm run compile

# watch typescript files for changes
$ npm run watch

# run the app
$ npm start

# create distributable packages for specific platforms
$ npm run dist-linux
$ npm run dist-mac
$ npm run dist-windows
```

## Directory Structure

<pre>
.
├── electron-builder.json <b>(electron-builder configuration)</b>
├── .gitignore
├── LICENSE.md
├── package.json
├── package-lock.json
├── README.md
├── src <b>(typescript files go here)</b>
│   ├── main.ts
│   ├── preload.ts
│   └── renderer.ts
├── tsconfig.json <b>(typescript compiler options)</b>
├── tslint.json <b>(tslint configuration)</b>
├── views <b>(html, css files go here)</b>
│   └── index.html
└── .vscode
    └── launch.json <b>(vscode debugger configuration)</b>
</pre>

## Resources

- [Electron docs](https://www.electronjs.org/docs)
- [electron-builder docs](https://www.electron.build)
- [Typescript docs](https://www.typescriptlang.org/docs)
- [Tslint docs](https://palantir.github.io/tslint/usage/configuration)
