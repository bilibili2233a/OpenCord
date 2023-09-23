<h1 align="center">OpenCord</h1>
<p align="center">
  <a href="https://discord.gg/3y6vbneMsW">
    <img alt="Discord" src="https://img.shields.io/discord/885879572447522817.svg?label=OpenCord&logo=discord&style=for-the-badge&logoColor=FFFFFF">
  </a>
</p>
<p align="center">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/MateriiApps/OpenCord?logo=github&style=for-the-badge">
  <img alt="GitHub forks" src="https://img.shields.io/github/forks/MateriiApps/OpenCord?logo=github&style=for-the-badge">
  <a href="https://github.com/MateriiApps/OpenCord/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/github/license/MateriiApps/OpenCord?color=%23007ec6&style=for-the-badge">
  </a>
  <a href="https://crowdin.com/project/opencord">
    <img alt="Crowdin" src="https://badges.crowdin.net/opencord/localized.svg">
  </a>
  <br/>
  <p align="center">
    一款 Material You 实现的 Discord Android 开源应用。（正在进行中）
  </p>
</p>

## 预览图

|                          Chat                           |                          Drawer                           |
|:-------------------------------------------------------:|:---------------------------------------------------------:|
|    <img src=".github/assets/chat.png" width="200"/>     |    <img src=".github/assets/drawer.png" width="200"/>     |
| <img src=".github/assets/themed_chat.png" width="200"/> | <img src=".github/assets/themed_drawer.png" width="200"/> |

## FAQ

### 此客户端是否支持“插件”或自定义功能/主题？

在未来很有可能实现，但我们的首要任务是实现Stock客户端的大部分功能。要查看我们当前的进度，请参阅STATUS.md。随时欢迎您创建和添加功能，或私下进行！

### Discord TOS反对吗？

是的，是的。然而，从没有过因为使用修改过的客户端而禁止用户使用“Discord”的案例。它们会自动禁止API滥用或奇怪的请求。因此，OpenCord在模拟官方客户端时非常谨慎，但由于它仍在开发中，为了您的安全，请使用alt帐户。***

### 在哪里下载????!

由于OpenCord还没有发布版本，请在GitHub Actions下载OpenCord。下载后解压并安装中包含的APK。如果要重新安装或更新，必须先卸载旧版本！“签名不一致”

## 本地构建

Windows系统:

```batch
.\gradlew.bat app:assembleDebug
```

Linux/macOS系统:

```shell
./gradlew app:assembleDebug
```

生成的 APK 将在此处： `app/build/outputs/apk/debug/app-debug.apk`
