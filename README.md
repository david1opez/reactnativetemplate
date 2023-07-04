# React Native Template

1. git clone https://github.com/david1opez/reactnativetemplate
2. cd <<cloned repository directory>>
3. npm install
4. change app-name && app version on package.json, package-lock.json, app.config.ts
5. eas build:config
6. npx expo prebuild --clean
7. eas build --profile development --platform android
8. npx expo start --dev-client
