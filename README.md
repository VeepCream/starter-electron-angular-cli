# Test3

This project was generated with [angular-cli](https://github.com/angular/angular-cli) version 1.0.0-beta.28.3.

## Development server
Run `npm run start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng g component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class/module`.

## install

npm i

## Build

npm run start : "ng serve",
npm run build : "ng build",
npm run prepare : "cp -a electron/. dist",
npm run electron : "ng build && npm run prepare && electron dist",
npm run package : "npm run build && npm run prepare && ./node_modules/electron-packager/cli.js dist App --platform=darwin --arch=all --out=dist-app --overwrite"