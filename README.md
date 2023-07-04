# React Native Template

1. git clone https://github.com/david1opez/reactnativetemplate
2. cd cloned repository directory
3. npm install
4. change app-name && app version on package.json, package-lock.json, app.config.ts
5. change package name in app.config.ts
6. eas build:config
7. npx expo prebuild --clean
8. eas build --profile development --platform android
9. npx expo start --dev-client
