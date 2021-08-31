[![GitHub issues](https://img.shields.io/github/issues/bhishaksanyal/react-native-typescript-template)](https://github.com/bhishaksanyal/react-native-typescript-template/issues)
[![GitHub forks](https://img.shields.io/github/forks/bhishaksanyal/react-native-typescript-template)](https://github.com/bhishaksanyal/react-native-typescript-template/network)
[![GitHub stars](https://img.shields.io/github/stars/bhishaksanyal/react-native-typescript-template)](https://github.com/bhishaksanyal/react-native-typescript-template/stargazers)
[![GitHub license](https://img.shields.io/github/license/bhishaksanyal/react-native-typescript-template)](https://github.com/bhishaksanyal/react-native-typescript-template/blob/main/LICENSE)
[![codecov](https://codecov.io/gh/bhishaksanyal/react-native-typescript-template/branch/main/graph/badge.svg?token=0SEFICI138)](https://codecov.io/gh/bhishaksanyal/react-native-typescript-template)

# React Native Typescript Starter Template

A react-native typescript starter template with inbuilt ready to use Eslint, Prettier, Jest and Typescript setup.

### Getting Started
#
1. Clone and install
```
# Clone the repo
git clone https://github.com/bhishaksanyal/react-native-typescript-template.git

# Navigate to clonned folder and Install dependencies
cd react-native-typescript-template && yarn install

# Install Pods
cd ios && pod install
```

2. Rename the project
```
yarn rename <PROJECT_NAME>
```
3. Migrate to AndroidX to support [React Native 0.60](https://reactnative.dev/blog/2019/07/03/version-60#androidx-support)
```
yarn jetify
```
4. Remove .git
```
rm -rf .git
```
5. Run in iOS simulator
```
yarn ios
```
6. Run in Android simulator
```
yarn android
```


### Typescript (https://www.typescriptlang.org/)
#
TypeScript is a strongly typed programming language which builds on JavaScript giving you better tooling at any scale.

## What is TypeScript?
1. JavaScript and More

`
    TypeScript adds additional syntax to JavaScript to support a tighter integration with your editor. Catch errors early in your editor.
`

2. A Result You Can Trust

`
    TypeScript code converts to JavaScript which runs anywhere JavaScript runs: In a browser, on Node.js or Deno and in your apps.
`

3. Safety at Scale

`
    TypeScript understands JavaScript and uses type inference to give you great tooling without additional code.
`