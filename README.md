# Hobbe Application [iOS/Android]

[![React Native](https://img.shields.io/badge/React%20Native-v0.57.8-blue.svg)](https://facebook.github.io/react-native/)
[![Expo](https://img.shields.io/badge/Expo-SDK35.0.0-black.svg)](https://expo.io/)
[![React Redux V6](https://img.shields.io/badge/Redux-v6.0.1-purple.svg)](https://react-redux.js.org/)
[![React Navigation V3](https://img.shields.io/badge/React%20Navigation-v3.4.1-blue.svg)](https://reactnavigation.org/)
[![Amazon AWS](https://img.shields.io/badge/amazonaws-v3.4.1-blue.svg)](https://aws.amazon.com/)
[![Socket IO](https://img.shields.io/badge/Socket.io-v2.2.0-black.svg)](https://socket.io/)

<p align="center" >
   <a href="https://github.com/AbdeenM/hobee-application/blob/master/screenshots/application.gif">
    <img alt="hobee-application" src="https://github.com/AbdeenM/hobee-application/blob/master/screenshots/application.gif" />
 </a>
</p>

Hobee Application is a social networking application, users can create/join activites and events they are intrested in around there area.
Users can view activties through searching, browsing or looking around the map.

## Features

* [React Navigation](https://reactnavigation.org/)
* [Redux](https://redux.js.org/)
* [Redux Thunk](https://github.com/reduxjs/redux-thunk/)
* [React Native Maps](https://github.com/react-native-community/react-native-maps/)
* [React Native Elements](https://react-native-training.github.io/react-native-elements/)
* [Lottie React Native](https://github.com/react-community/lottie-react-native/)
* [MomentJs](https://momentjs.com/)
* [React Native Gifted Chat](https://github.com/FaridSafi/react-native-gifted-chat/)
* [React Native Vector Icons](https://github.com/oblador/react-native-vector-icons/)

... and many more, check the package.json file for all the libraries used.

## Prerequisites

* [Hobee Backend Server](https://github.com/AbdeenM/hobee-backend/) (Required, this is your Hobee application server, daa!)
* [Node](https://nodejs.org/) v10.16.0 (it is recommended to install it via [NVM](https://github.com/creationix/nvm/))
* [NPM](https://npmjs.com/) or [Yarn](https://https://yarnpkg.com/)
* A development enviroment setup with React Native and Expo, you can follow [these instructions](https://docs.expo.io/versions/v35.0.0/introduction/installation/) (Required as project core)
* Google Maps Api key, you can follow [these instructions](https://developers.google.com/maps/documentation/javascript/get-api-key/) (Optional, for map to work)
* Facebook App Id, you can follow [these instructions](https://docs.expo.io/versions/v35.0.0/sdk/facebook/) (Optional, for facebook login to work)
* Google Clients Id, you can follow [these instructions](https://docs.expo.io/versions/v35.0.0/sdk/google/) (Optional, for google login to work)
* Amazon AWS Account with S3 access rights, you can follow [these instructions](https://aws.amazon.com/s3/getting-started/) (Optional, to save images in your AWS Server)

#### Note: AWS is currently commented out to activate it have an amazon bucket setup with the right permissions and edit `screens/createHobee/CreateHobeeScreet.js` and uncomment `line 142` to `line 165`

## Installation

Following this assumes you have everything setup, to install the project either download the .zip file and extract or navigate to an empty directory and clone this repo:
```bash
git clone https://github.com/AbdeenM/hobee-application.git
```
Once you have the project files downloaded navigate to where the `package.json` file is in your directory and run `npm install` or `yarn install` depending on what you have as a package manager.

## Getting Started

0. Setup [Hobee Server](https://github.com/AbdeenM/hobee-backend/).
1. Modify `constants/Config.js` with your details respectively.
2. Run `expo start` on the project root directory.
3. Download the Expo app depending on your smart phone and Scan the QR code to open the application on your device.
4. Now sit back relax and enjoy exploring the application!

## Contributing

Pull requests are welocme. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.


## License

[MIT](https://choosealicense.com/licenses/mit/)
