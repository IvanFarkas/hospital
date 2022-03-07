# monorepo with Lerna for a TypeScript project

[Article](https://blog.logrocket.com/setting-up-monorepo-with-lerna-typescript)
[GitHub](https://github.com/vladotesanovic/hospital-sdk)
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
lerna bootstrap
cd packages/integration
npm start
cd ../../
```

## npm

```shell
npm login --scope=3dhd_org
npm notice Log in on https://registry.npmjs.org/
Username: 3dhd_dev
Password: 
Email: (this IS public) 3dhd_dev@3DHDSoft.com
npm notice Please use the one-time password (OTP) from your authenticator application
Enter one-time password: 000000
Logged in as 3dhd_dev to scope @3dhd_org on https://registry.npmjs.org/.
```
