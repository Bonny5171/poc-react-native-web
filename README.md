# Poc react-native-web

App para IOS, Android e Web. Construida com create-react-app e create-react-native-app contendo estrutura basica de autenticação, globalizando e rotas.

### Utilizado: Redux, Jest, Enzyme e React-Router

[Mais detalhes no artigo](https://medium.com/@Or_yoffe/building-a-platfGlobalgzandonostic e rotas.-app-react-native-and-web-c0e82cbdda8)

<p align="center">
<img src="https://raw.githubusercontent.com/VISI-ONE/rnw-starter-app/master/src/assets/logo.png">width="300">
</p>

## Baseando em:
- [React Native for Web (react-native-web)](https://github.com/necolas/react-native-web)
- [React Everywhere boilerplate (react-native-template-re-start)](https://github.com/react-everywhere/re-start)
- [React](https://reactjs.org/)
- [React Native](http://facebook.github.io/react-native/)
- [Redux](https://redux.js.org/)
- [React Router](https://reacttraining.com/react-router/native/)
- [Jest](https://facebook.github.io/jest/) para os testes
- [Enzyme](http://airbnb.io/enzyme/) para os testes

## Instalação

- Instalar yarn package manager (1.3.2): `npm i -g yarn`
- Instalar node (minimum: node v8.9.1) through [nvm (Node version manager)](https://github.com/creationix/nvm)
- Instalar [adb (Android Debug Bridge)](https://developer.android.com/studio/releases/platform-tools.html)


- Clone o repositorio e instalar as dependencias
```
npm -g i react-native-cli
git clone git@bitbucket.org:luis_araujo/poc-react-native-web.git
cd poc-react-native-web
rm -rf .git
yarn install
yarn
```

- instalar o Xcode, android studio e o react-native [Construindo projetos com código nativo]
(http://facebook.github.io/react-native/docs/getting-started.html)

## Running

- Native - `yarn start`
- Web - `yarn web`
- IOS Simulator - `yarn ios`
- Android Simulator - `yarn android`


## Testes

- Eslint - `yarn lint`
- Eslint fix - `yarn lint-fix`
- Web - `yarn test:web`

- Web watch mode - `yarn test:web-watch`

- Native - `yarn test:native`

- Web watch mode - `yarn test:native-watch`

- Coverage - web `yarn coverage`
- Coverage - native `yarn coverage:native`
- Open Coverage - web `yarn open-coverage`
- Open Coverage - native `yarn open-coverage:native`

## Debugando

Abrir o menu de desenvolvedor:
1. CMD+D (IOS) / CMD+M (Android)
2. Pressione "Enable Live-Reload"

[Em dispositivos reais](http://facebook.github.io/react-native/releases/0.49/docs/running-on-device.html)
[React native docs](http://facebook.github.io/react-native/docs/debugging.html)


## Build
- WEB - run `yarn build`
- Android - [React native docs](http://facebook.github.io/react-native/releases/0.49/docs/signed-apk-android.html)
- IOS - [React native docs](http://facebook.github.io/react-native/releases/0.49/docs/running-on-device.html#building-your-app-for-production)


## Atalhos
- Ver com atenção o package.json scripts
