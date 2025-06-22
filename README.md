WebESPFlash
----

### 基于ESP Launchpad开发的中文特供版，也许会增加一些功能捏～

**ESP Launchpad** 是一个基于 Web 的工具，可用于将固件应用程序刷入通过 USB 串行端口连接的 ESP32 设备。**此版本的翻译由[EterIll](https://github.com/EternalIllusion)贡献。**

有两种模式可使用此工具：

 - 快速开始 : 4 个简单的步骤 - 插入、连接、选择、刷写！     
 - 自定义 : 对于高级用户，使用您自己从本地存储中预构建的固件映像！

您甚至可以使用 ESP Launchpad 为 ESP32 构建和发布自己的应用程序！

## 快速开始

ESP 目前提供了一些内置的可以在 ESP32 设备上刷写的即用型示例。您可以根据芯片组类型，选择 RainMaker 或 Matter 的应用程序内置固件。您只需将 ESP32 设备插入USB串口即可，然后使用菜单中的 connect 选项连接到您的 ESP32 设备，接着从示例集中选择固件，单击烧录！

固件将刷入您连接的设备。您也可以在控制台窗口中查看固件烧写的进度。

这个简单的 4 步过程会将固件刷入连接的设备，并按照您的意愿使其发光发热（确信）。

[握草，赶紧让爷试试!](https://esp.eterill.xyz/)

## 自定义

您可以使用 ESP IDF 工具构建自己的固件二进制，然后将这些固件映像从本地刷写到连接的设备。只需将您的 ESP32 设备连接到USB串口即可使用工具连接到您的设备，然后从本地存储中选择固件和要刷写的固件的内存地址。固件可以是单个文件，也可以是一组要在特定内存地址刷写的多个文件。

点击烧录!

固件将刷入您连接的设备。您也可以在控制台窗口中查看固件烧写的进度。

[赶紧让爷看看!](https://esp.eterill.xyz/)

## 发布您自己的固件应用程序

ESP Launchpad 还允许您轻松发布固件应用程序供其他人尝试。

ESP Launchpad 快速入门页面将通过引用 TOML 配置文件来呈现，您可以在其中配置从何处选择固件的所有组件镜像以及支持的硬件。您还可以链接到任何支持的手机应用程序来使用此固件。您可以在 [这里](https://github.com/espressif/esp-launchpad/blob/main/config/config.toml) 查看示例 TOML 配置文件

其余的刷写过程与上面的快速入门过程相同，只需 4 个步骤即可。

完成后，您可以在您的网站上添加以下 html 代码，以便通过您的配置支持 ESPaunchpad。编辑 href 中的参数，替换URL_TO_YOUR_CONFIG_TOML为您托管 TOML 配置文件的URL值。

```
<a href="https://esp.eterill.xyz/?flashConfigURL=URL_TO_YOUR_CONFIG_TOML">
    <img alt="使用ESP Launchpad一键烧录！" src="https://esp.eterill.xyz/assets/try_with_launchpad.png" width="250" height="70">
</a>
```
