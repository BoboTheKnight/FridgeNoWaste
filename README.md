[![Java CI](https://img.shields.io/github/actions/workflow/status/BoboTheKnight/fridge-no-waste/ci.yml?branch=master&logo=github)](https://github.com/BoboTheKnight/fridge-no-waste/actions/workflows/ci.yml)
&nbsp;
[![Codecov](https://img.shields.io/codecov/c/github/BoboTheKnight/fridge-no-waste/master?logo=codecov&logoColor=white)](https://codecov.io/gh/alibaba/fastjson2/branch/main)
&nbsp;
[![Java support](https://img.shields.io/badge/Java-8+-green)](https://openjdk.java.net/)
&nbsp;
[![License](https://img.shields.io/badge/license-MIT-blue?logo=opensourceinitiative&logoColor=white)](https://github.com/BoboTheKnight/fridge-no-waste/blob/master/LICENSE)
&nbsp;
[![GitHub Contributors](https://img.shields.io/github/contributors/BoboTheKnight/fridge-no-waste)](https://github.com/BoboTheKnight/fridge-no-waste/graphs/contributors)

##### 📖 English Documentation | 📖 [中文文档](https://github.com/BoboTheKnight/fridge-no-waste/blob/master/README-zh.md)

FridgeNoWaste: Keep food from being wasted!
---
FridgeNoWaste is a web and mobile application aimed at helping people reduce food waste by keeping track of the contents of their fridge and suggesting recipes based on those contents.

<!-- TOC -->
## Table of Contents
 * [Features](#features)
 * [Technologies](#technologies)
 * [Installation](#installation)
 * [Usage](#usage)
 * [Contributing](#contributing)
 * [License](#license)
<!-- TOC -->

### Features
- [ ] Allows users to create an account and add their fridge contents.
- [ ] Enables users to input their fridge contents by scanning barcodes or using OCR technology to make the process easier.
- [ ] Displays the expiration dates of the items in the user's fridge and sends reminders before the food expires.
- [ ] Supports multiple languages.
- [ ] Provide a list of foods added in history to simplify the operation process.
- [ ] Provides information on how to store different types of food to prolong their shelf life.
- [ ] Suggests recipes based on the contents of the user's fridge.
- [ ] Supporting multiple recipes.
- [ ] Allows users to search for recipes by ingredients and save their favorite recipes.
- [ ] Allows users to create a home, manage home members, and share refrigerator contents with other home members. 
- [ ] Builds rewards to encourage users to keep track of their fridges and reduce food waste.
- [ ] Generates statistics about how much food users are saving and their contribution to reducing food waste.

### Technologies
The FridgeNoWaste project uses the following technologies:
- Java
- Spring Boot
- React
- React Native
- Maven

### Installation
To use FridgeNoWaste, you need to have Java, Node.js, and npm installed on your machine.

To clone the repository and set up the project, run the following commands in your terminal:
```bash
git clone https://github.com/BoboTheKnight/fridge-no-waste.git
cd fridge-no-waste/backend
./mvnw spring-boot:run
```

To start the React web application, run the following commands in another terminal:
```bash
cd fridge-no-waste/frontend
npm install
npm start
```

To start the React Native mobile application, run the following commands in another terminal:
```bash
cd fridge-no-waste/mobile
npm install
npx react-native run-android
```

iOS
To run the iOS application, you need to have Xcode installed on your machine. You can then run the application by typing `npx react-native run-ios` in the terminal. Alternatively, you can open the `ios/fridge-no-waste.xcodeproj` file in Xcode and run the application from there.

### Usage
Once you have set up the project, you can access the web application by visiting `http://localhost:3000/` in your web browser. You can create an account, add items to your fridge, and search for recipes based on the contents of your fridge.

To use the mobile application, you can either use an Android emulator or a physical Android device connected to your machine (as explained in the previous section), or an iOS simulator or a physical iOS device connected to your machine (by following the instructions in the "iOS" section above).

### Contributing
If you want to contribute to FridgeNoWaste, you can follow these steps:

1. Fork the repository.
2. Create a new branch with your changes: `git checkout -b my-feature-branch`
3. Make changes and commit them: `git commit -am 'Add new feature'`
4. Push your changes to the branch: `git push origin my-feature-branch`
5. Submit a pull request.

### License
FridgeNoWaste is released under the [MIT License](https://opensource.org/license/mit/). See [LICENSE](https://github.com/BoboTheKnight/fridge-no-waste/blob/master/LICENSE) for more information.