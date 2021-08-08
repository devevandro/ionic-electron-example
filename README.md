# Desktop project build with ionic-capacitor-angular and Electron JS

Description

- create an project with ionic-capacitor angular:
```shell
ionic start example blank --type=angular --capacitor
```

- or if you have been a project just enable capacitor in your project:
```shell
ionic integrations enable capacitor
```

- install @capacitor-community/electron:
```shell
npm install @capacitor-community/electron
```

- project build:
```shell
ionic build --prod --release
```

- adding capacitor electron platform:
```shell
npx cap add @capacitor-community/electron
```

- launch project:
```shell
npx cap open @capacitor-community/electron
```

- to customizing the electron options:
electron/src/index.ts

- oficial documentation;
https://capacitor-community.github.io/electron/#/./

- oficial github:
https://github.com/capacitor-community/electron
