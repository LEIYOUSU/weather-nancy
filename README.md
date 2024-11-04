# Weather-Nancy

## 项目简介
**Weather-Nancy** 是我在大二下学期 Android 课程中完成的一款综合性 Android 应用，目前正在不断完善和修改。该应用提供天气查询、音乐播放和日程管理功能。用户可以获取实时天气数据、播放本地和在线音乐，并管理个人日程安排。

## 演示视频
您可以通过以下链接查看项目的效果视频：  
[项目效果视频](https://github.com/user-attachments/assets/19ecfa22-f642-4650-a78b-cb8f81979700)

## 开发者配置流程
1. **克隆项目**：
   - 首先，将项目克隆到本地。打开终端并运行以下命令：
     ```bash
     git clone https://github.com/your-username/weather-nancy.git
     ```
   - 替换 `your-username` 为你的 GitHub 用户名。
2. **查看 SHA**：
   - 在项目目录中找到 `app` 文件夹，并根据您的开发环境生成 SHA-1 密钥。您可以使用以下命令：
     ```bash
     keytool -list -v -keystore ~/.android/debug.keystore -alias androiddebugkey -storepass android -keypass android
     ```
   - 记录下生成的 SHA-1，后续需要用于百度 SDK 注册。
3. **注册百度 SDK**：
   - 前往 [百度地图开放平台](https://lbsyun.baidu.com/) 注册账号。
   - 登录后进入控制台，选择“应用管理”，创建新的应用，并按照提示配置 SHA-1。
4. **下载依赖**：
   - 根据项目的 Gradle 配置文件（`build.gradle`）下载相应的 Gradle 版本及其他依赖包。
   - 确保您的 `Gradle` 版本与项目一致，推荐使用 Gradle 8.4。
5. **配置 Android Studio**：
   - 打开 Android Studio，选择“打开项目”，找到您克隆的项目目录。
   - 在项目根目录下的 `build.gradle` 文件中，检查 SDK 和依赖配置是否正确。
6. **连接真机**：
   - 确保您的 Android 设备已开启开发者模式。您可以通过在“设置”中找到“关于手机”，然后连续点击“版本号”七次来激活开发者选项。
   - 在开发者选项中，启用“USB 调试”。
7. **运行项目**：
   - 在 Android Studio 中，点击“运行”按钮，选择连接的真机进行部署。
   - 如果应用无法获取天气信息，请检查和风天气 API 是否有效。
8. **提交修改**：
   - 在完成您的更改后，使用 Git 提交您的代码：
     ```bash
     git add .
     git commit -m "描述您的更改"
     git push origin main
     ```
   - 提交 Pull Request，欢迎其他开发者进行审阅和讨论。

## 安装环境
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

![和风天气 API 配置示例](https://github.com/user-attachments/assets/3d9f9ae9-6aaa-4327-bc36-efe676cf713c)

## 安装过程中可能遇到的问题
1. **Gradle 构建出现问题**：建议使用 Gradle 8.4，避免版本冲突或不一致导致的问题。
2. **和风天气 API 失效**：需自行前往和风控制台进行开发者注册，选择标准订阅即可，可以选择自行配置。在 `Constant` 中修改 API 常量。
3. **无法定位**：确保在 Android 真机上运行，并在手机设置中双击系统版本号以开启开发者模式。

## 联系方式
如有问题，请联系我：  
**Email**: [1737165074@qq.com](mailto:1737165074@qq.com)
