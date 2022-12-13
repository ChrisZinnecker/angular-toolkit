# `@ionic/cordova-builders`

A collection of builders for `@ionic/angular` projects using Cordova.

To add these builders to your project, run

```shell
ng add @ionic/cordova-builders
```

## Commands for Copy to Ionic Project

```bash
rsync -avuP --exclude .git --exclude node_modules ../angular-toolkit/packages/cordova-builders/ ../JCO/node_modules/@ionic/cordova-builders
rsync ../angular-toolkit/packages/cordova-builders/package.json ../JCO/node_modules/@ionic/cordova-builders/
rsync -avuP --exclude .git --exclude node_modules ../angular-toolkit/ ../JCO/node_modules/@ionic/angular-toolkit
rsync ../angular-toolkit/package.json ../JCO/node_modules/@ionic/angular-toolkit/
```
