# An desktop project build with ionic-capacitor-angular and electron js
# An simple example

Description

-- create an project with ionic-capacitor angular:
```shell
ionic start example blank --type=angular --capacitor
```

-- or if you have been an project enable capacitor in your project:
```shell
ionic integrations enable capacitor
```

-- install @capacitor-community/electron:
```shell
npm install @capacitor-community/electron
```

-- project build:
```shell
ionic build --prod --release
```

-- adding capacitor electron platform:
```shell
npx cap add @capacitor-community/electron
```

-- launch project:
```shell
npx cap open @capacitor-community/electron
```

-- to customizing the electron options:
electron/src/index.ts

-- oficial documentation;
https://capacitor-community.github.io/electron/#/./

-- oficial github:
https://github.com/capacitor-community/electron
#   i o n i c - e l e c t r o n - e x a m p l e  
 