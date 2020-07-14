# ESLINT-CONFIG-REACT-NATIVE-GERARDKETUMA

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
