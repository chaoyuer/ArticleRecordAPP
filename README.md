# ArticleRecordAPP
# 物品记录APP，使用 React Native 开发

#### 软件架构
1. 框架：React Native  https://www.reactnative.cn/
2. 路由：React Navigation https://reactnavigation.org/

#### 安装与运行
1. 安装依赖 yarn
2. 运行项目 npx react-native run-android

#### 打包
1. 在android目录下，使用命令行执行 gradlew assembleRelease
2. 打包完成后，安装包在 android\app\build\outputs\apk\release 中
3. 可以参考：https://www.reactnative.cn/docs/signed-apk-android
4. 注：打包前需要配置签名

#### 使用说明
1. App.js 入口文件主要提供路由
2. src/page/Home.js 中为主页面，用于路由跳转
3. 注意：文件名后缀不要使用 .jsx，会识别不到
4. 终端中使用命令 “npx react-native log-android” 可以看到console.log()的信息

