# ESLINT-CONFIG-REACT-NATIVE-GERARDKETUMA
This is my eslint configuration for React Native. I use this across all my React Native projects.

## INSTALLATION
```
yarn add eslint prettier typescript eslint-config-react-native-gerardketuma --dev
```
*Note: I'm using `yarn` to install deps. Feel free to change commands to use `npm` 3+ and `npx` if you like*

## USAGE
Add to your eslint config (`.eslintrc`, or `eslintConfig` field in `package.json`):
```json
{
  "extends": "react-native-gerardketuma"
}
```
*Since this project lints TypeScript projects, you must have a tsconfig.json file in your root directory.*