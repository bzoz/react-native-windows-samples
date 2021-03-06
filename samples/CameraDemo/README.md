# CameraDemo - React Native for Windows

<p align="center">
  <a href="https://github.com/microsoft/react-native-windows-samples/actions?query=workflow%3A%22CameraDemo+CI%22">
    <img src="https://github.com/microsoft/react-native-windows-samples/workflows/CameraDemo%20CI/badge.svg" alt="CameraDemo CI Status" />
  </a>
</p>

This sample showcases the usage of React Native for Windows to build an app which consumes an external community module, in this case, [react-native-camera](https://github.com/react-native-community/react-native-camera).

It currently targets React Native Windows 0.63.

### Setup
First, make sure you've met the [React Native Windows System Requirements](https://microsoft.github.io/react-native-windows/docs/rnw-dependencies).

You'll also need a camera device connected to your machine.

Then, within this folder, install the applications's dependencies. If you have `yarn` installed:

```cmd
yarn install
```

Otherwise, you can just use npm:

```cmd
npm install
```

### Run
Once you have all of the dependencies installed, you can run the application with the following command:

```cmd
npx react-native run-windows
```

The command will:
* Build the application and all dependencies
* Deploy the application
* Launch the React Native Server and Debugger
* Launch the application
