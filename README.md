# Weather-Nancy

## 项目简介
**Weather-Nancy** 是我在大二下学期 Android 课程中完成的一款综合性 Android 应用，目前正在不断完善和修改。该应用提供天气查询、音乐播放和日程管理功能。用户可以获取实时天气数据、播放本地和在线音乐，并管理个人日程安排。

## 演示视频
您可以通过以下链接查看项目的效果视频：  
[项目效果视频](https://github.com/user-attachments/assets/19ecfa22-f642-4650-a78b-cb8f81979700)

## 安装说明
1. **开发工具**：Android Studio（版本：Dolphin | 2021.3.1，建议使用该版本或更高版本）
2. **开发语言**：Java
3. **JDK版本**：Java 11（请确保在电脑中配置环境变量）
4. **Android版本**：Android 12
5. **Gradle版本**：8.4
6. **SDK**：
   - Compile SDK Version: 34
   - Min SDK Version: 23
   - Target SDK Version: 28
7. **数据库**：SQLite
8. **运行设备**：请使用 Android 真机（不要使用模拟器或虚拟机，因为模拟器无法实现定位，需在真机上开启开发者模式）。
9. **下载百度SDK**：需要使用百度定位、地图等功能，请在百度地图开放平台上注册。注册后进入控制台 → 应用管理 → 我的应用 → 创建应用，并完成相应的 SHA 配置。
10. **注册和风天气 API（可选）**：如果项目中的和风天气 API 因访问过多而失效，可以选择自行配置。在 `Constant` 中修改 API 常量。

![和风天气 API 配置示例](https://github.com/user-attachments/assets/3d9f9ae9-6aaa-4327-bc36-efe676cf713c)

## 安装过程中可能遇到的问题
1. **Gradle 构建出现问题**：建议使用 Gradle 8.4，避免版本冲突或不一致导致的问题。
2. **和风天气 API 失效**：需自行前往和风控制台进行开发者注册，选择标准订阅即可。
3. **无法定位**：确保在 Android 真机上运行，并在手机设置中双击系统版本号以开启开发者模式。

## 联系方式
如有问题，请联系我：  
**Email**: [1737165074@qq.com](mailto:1737165074@qq.com)
