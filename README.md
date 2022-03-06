# monorepo with Lerna for a TypeScript project

[Article](https://blog.logrocket.com/setting-up-monorepo-with-lerna-typescript)
[GitHub](https://github.com/vladotesanovic/hospital)
[lerna](https://github.com/lerna)

## Requirements

```
Node >= 16
```

## Install deps

Please make sure you have the required packages. This app uses yarn and webpack. To install the dependencies, please run the following commands:

```
npm i -g lerna ts-node
mkdir hospital && cd hospital
lerna init && npm install
npm install typescript @types/node — save-dev
```

## Run

```shell
yarn install
yarn build
yarn start
```

## npm

```shell
npm login --scope=3dhdsoft_org
```
