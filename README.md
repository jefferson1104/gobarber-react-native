<div align="center" style="margin-bottom: 20px;">
  <img alt="gobarber" src="/assets/img/goBarber-logo.svg" width="auto" heigth="auto"/>
  <p align="center" style="margin-top: 20px;">
    <img alt="technology" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white">
    <img alt="technology" src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
    <img alt="technology" src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white">
  </p>
</div>

## :barber: About this project

This project is a mobile version of the gobarber project, its source code was developed with React Native technology to work on Android and IOS devices.

<div align="center">
  <img alt="gobarber" src="/assets/img/mobile-screenshot.png" width="200"/>
</div>

## :rocket: Main technologies
- [TypeScript](https://www.typescriptlang.org/docs/)
- [React Native](https://reactnative.dev/)
- [Axios](https://github.com/axios/axios)
- [Styled-Components](https://styled-components.com/)

## :zap: How to run this project
To start the **gobarber** application in the mobile version (APP) it is also necessary that the [Back-end (API)](https://github.com/jefferson1104/gobarber-nodejs) of the project is started and in execution, also make sure you have an environment configured to run a smartphone emulator on your computer, on my machine I used an android emulator from android studio itself, AVD (Android Virtual Device) use a vm with at least android Pie 9 or more updated, and a version also with access to google play, in my example I used a vm from **_Google Pixel 3a_**

You can also use Expo, for that know how to configure the expo on your computer to emulate or even use your own smartphone.

<div align="center" style="margin-bottom: 20px;">
  <img alt="gobarber" src="/assets/img/screenshot_avd.png" width="auto" heigth="auto"/>
</div>

> **IMPORTANT**: If you use the same method as me to run the application in an android studio emulator, right after starting the emulator it is important to run the command `adb reverse tcp:3333 tcp:3333` in the terminal to have communication with the emulator and you can install the goBarbar app.

#### To start the mobile version (APP) of the project:
```Bash
# Access the mobile directory
$ cd gobarber-react-native

# Install all project dependencies
$ yarn

# Assuming your emulator is already started and you have already run the reverse command, install the application on the emulator.
$ yarn android

# Launch app in emulator
$ yarn start
```
