[![Java CI](https://img.shields.io/github/actions/workflow/status/BoboTheKnight/fridge-no-waste/ci.yml?branch=master&logo=github)](https://github.com/BoboTheKnight/fridge-no-waste/actions/workflows/ci.yml)
&nbsp;
[![Codecov](https://img.shields.io/codecov/c/github/BoboTheKnight/fridge-no-waste/master?logo=codecov&logoColor=white)](https://codecov.io/gh/alibaba/fastjson2/branch/main)
&nbsp;
[![Java support](https://img.shields.io/badge/Java-8+-blue)](https://openjdk.java.net/)
&nbsp;
[![License](https://img.shields.io/github/license/BoboTheKnight/fridge-no-waste?logo=opensourceinitiative&logoColor=white)](https://github.com/BoboTheKnight/fridge-no-waste/blob/master/LICENSE)
&nbsp;
[![GitHub Contributors](https://img.shields.io/github/contributors/BoboTheKnight/fridge-no-waste)](https://github.com/BoboTheKnight/fridge-no-waste/graphs/contributors)

##### 📖 [English Documentation](https://github.com/BoboTheKnight/fridge-no-waste/blob/master/README.md) | 📖 中文文档


FridgeNoWaste: 让食物不再被浪费！
---

FridgeNoWaste是一款网络和移动应用程序，旨在通过跟踪冰箱中的物品并根据这些物品推荐食谱来帮助人们减少食物浪费。

<!-- TOC -->
## 目录
* [特性](#特性)
* [技术](#技术)
* [安装](#安装)
* [使用](#使用)
* [贡献](#贡献)
* [许可协议](#许可协议)
<!-- TOC -->

### 特性
- [ ] 创建账户，添加冰箱内的食品
- [ ] 允许用户通过扫描条形码或使用OCR技术提取文字，从而简化录入流程
- [ ] 显示最佳使用日期和过期时间，并允许用户设置自定义提醒
- [ ] 多语言支持
- [ ] 提供历史添加过的食品列表，简化操作流程
- [ ] 提供关于如何存储不同类型食物以延长它们保质期的信息
- [ ] 根据用户冰箱内食品推荐菜谱
- [ ] 多地区菜谱支持
- [ ] 根据成分选食谱，保存喜欢的食谱
- [ ] 允许用户创建家庭，管理家庭成员，并与其他家庭成员共享冰箱内容
- [ ] 建立奖励机制以鼓励用户跟踪他们的冰箱并减少食物浪费
- [ ] 生成有关食物用户节省多少以及他们对减少食物浪费的贡献的统计数据

### 技术
FridgeNoWaste 项目使用了以下技术：
- Java
- Spring Boot
- React
- React Native
- Maven

### 安装
要使用 FridgeNoWaste，您需要安装 Java、Node.js 和 npm。

要克隆存储库并设置项目，在终端中运行以下命令：
```bash
git clone https://github.com/BoboTheKnight/fridge-no-waste.git
cd fridge-no-waste/backend
./mvnw spring-boot:run
```

要启动 React Web 应用程序，请在另一个终端中运行以下命令：
```bash
cd fridge-no-waste/frontend
npm install
npm start
```

要启动 React Native 移动应用程序，请在另一个终端中运行以下命令：
```bash
cd fridge-no-waste/android
npm install
npx react-native run-android
```

iOS
要运行 iOS 应用程序，您需要在计算机上安装 Xcode。 然后，您可以通过在终端中键入`npx react-native run-ios`来运行应用程序。 或者，您可以在 Xcode 中打开 ios/fridge-no-waste.xcodeproj 文件并从那里运行应用程序。

### 使用
设置项目后，您可以通过在 Web 浏览器中访问“http://localhost:3000/”来访问 Web 应用程序。 您可以创建一个帐户，将食物添加到冰箱，并根据冰箱中的食物搜索食谱。

要使用移动应用程序，您可以使用连接到您机器的 Android 模拟器或物理 Android 设备（如上一节所述），或者使用 iOS 模拟器或连接到您机器的物理 iOS 设备（按照 上面的“iOS”部分）。

### 贡献
如果你想为 FridgeNoWaste 做贡献，你可以按照以下步骤操作：

1. 分叉存储库。
2. 使用您的更改创建一个新分支：`git checkout -b my-feature-branch`
3. 进行更改并提交：`git commit -am 'Add new feature'`
4. 将您的更改推送到分支：`git push origin my-feature-branch`
5. 提交拉取请求。

### 许可协议
FridgeNoWaste 是根据 [MIT 许可证](https://opensource.org/license/mit/) 发布的。 有关详细信息，请参阅 [许可证](https://github.com/BoboTheKnight/fridge-no-waste/blob/master/LICENSE)。