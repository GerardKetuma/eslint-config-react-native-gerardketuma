# ESLINT-CONFIG-REACT-NATIVE-GERARDKETUMA

![CircleCI](https://img.shields.io/circleci/build/github/GerardKetuma/eslint-config-react-native-gerardketuma/master)
![npm](https://img.shields.io/npm/v/eslint-config-react-native-gerardketuma?style=flat-square)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

This is my eslint configuration for React Native. I use this across all my React Native projects.

## INSTALLATION

```
yarn add eslint prettier typescript eslint-config-react-native-gerardketuma --dev
```

_Note: I'm using `yarn` to install deps. Feel free to change commands to use `npm` 3+ and `npx` if you like_

## USAGE

Add to your eslint config (`.eslintrc`, or `eslintConfig` field in `package.json`):

```json
{
  "extends": "react-native-gerardketuma"
}
```

_Since this project lints TypeScript projects, you must have a tsconfig.json file in your root directory._

### Add Prettier config file

Since this package uses Prettier to format code styles, we suggest adding a prettier config file to the root directory and setting your code editor to use a prettier plugin.

#### Prettier Config:

```json
{
  "trailingComma": "es5",
  "tabWidth": 2,
  "semi": false,
  "singleQuote": true
}
```

#### VSCode Prettier Plugin:

[Prettier - Code Formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

#### VSCode ESLint Plugin:

[VS Code ESLint extension](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

Set VSCode to Auto Fix ESLint errors and warnings on save:

```json
"editor.codeActionsOnSave": {
  "source.fixAll.eslint": true
}
```
