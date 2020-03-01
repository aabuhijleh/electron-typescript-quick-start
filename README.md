# Electron TypeScript Quick Start

> This template is based on the official [electron-quick-start](https://github.com/electron/electron-quick-start) repository (but with typescript + prettier + electron-builder)

## How to use?

```sh
# install dependencies
$ npm install

# compile typescript files
$ npm run compile

# watch typescript files for changes (auto compilation)
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
├── .github <b>(github CI configuration)</b>
│   └── workflows
│       └── nodejs.yml
├── .gitignore
├── .huskyrc.json <b>(Husky configuration)</b>
├── LICENSE.md
├── .lintstagedrc.json <b>(lint-staged configuration)</b>
├── package.json
├── package-lock.json
├── .prettierignore
├── README.md
├── src <b>(typescript files go here)</b>
│   ├── main.ts
│   ├── preload.ts
│   └── renderer.ts
├── .stylelintrc.json <b>(stylelint configuration)</b>
├── tsconfig.json <b>(typescript compiler options)</b>
├── tslint.json <b>(tslint configuration)</b>
├── views <b>(html, css files go here)</b>
│   ├── index.css
│   └── index.html
└── .vscode
    ├── launch.json <b>(debugger configuration)</b>
    └── settings.json <b>(workspace settings)</b>
</pre>

## Resources

- [Electron docs](https://www.electronjs.org/docs)
- [electron-builder docs](https://www.electron.build)
- [Typescript docs](https://www.typescriptlang.org/docs)
- [Tslint docs](https://palantir.github.io/tslint/usage/configuration)
- [Stylelint docs](https://stylelint.io)
- [Prettier docs](https://prettier.io)
- [Husky](https://github.com/typicode/husky)
- [lint-staged](https://github.com/okonet/lint-staged)
- [Github CI](https://help.github.com/en/actions/building-and-testing-code-with-continuous-integration/about-continuous-integration)
