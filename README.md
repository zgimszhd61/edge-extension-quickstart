# edge-extension-quickstart
要快速开始Edge浏览器插件编程，你需要遵循一系列步骤来创建、开发和测试你的扩展。以下是一个基于Microsoft Edge扩展开发文档的简化流程：

### 准备工作

1. **了解基本概念**：首先，了解Microsoft Edge扩展是什么，以及它们如何工作。扩展是小型的软件程序，用于自定义浏览体验。它们可以增加新的功能或修改现有功能，以提高用户的浏览效率和体验[1]。

2. **熟悉必需的文件**：每个扩展至少需要包含三种文件：一个包含基本平台信息的`manifest.json`文件，一个定义扩展功能的JavaScript文件，以及一个定义用户界面的HTML和CSS文件[1]。

### 开始开发

1. **创建`manifest.json`文件**：这是每个扩展的核心文件，提供了扩展的名称、版本、权限等信息。以下是一个简单的`manifest.json`文件示例，用于创建一个显示NASA每日图片的扩展[4]：

```json
{
  "name": "NASA picture of the day viewer",
  "version": "0.0.0.1",
  "manifest_version": 3,
  "description": "An extension to display the NASA picture of the day."
}
```

2. **添加图标**：在你的项目中创建一个`icons`目录，并存储图标图像文件。图标是用户启动扩展时点击的按钮背景图像。建议使用128x128像素的PNG格式图像[4]。

3. **开发功能**：根据你的扩展需求，编写JavaScript和HTML/CSS文件。这些文件将定义你的扩展的功能和用户界面。

### 测试和调试

1. **加载你的扩展**：在Edge浏览器中，进入`edge://extensions/`页面，打开“开发者模式”，然后点击“加载已解压的扩展”，选择你的扩展目录。

2. **测试功能**：确保你的扩展按预期工作。你可以使用浏览器的开发者工具来调试JavaScript代码和检查用户界面。

### 发布和分享

完成开发和测试后，你可以考虑将你的扩展发布到Microsoft Edge Add-ons商店，以便其他用户可以下载和使用你的扩展。你需要遵循Microsoft的指南和要求来提交和发布你的扩展[1]。

以上步骤提供了一个Edge浏览器插件编程的快速开始指南。更详细的信息和指导，请参考Microsoft Edge扩展开发文档[1][4]。

Citations:
[1] https://learn.microsoft.com/zh-cn/microsoft-edge/extensions-chromium/
[2] https://juejin.cn/post/7299384357826510882
[3] https://www.youtube.com/watch?v=MP96vUloWHo
[4] https://learn.microsoft.com/zh-cn/microsoft-edge/extensions-chromium/getting-started/part1-simple-extension
[5] https://chromewebstore.google.com/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk
[6] https://en.antelopeaudio.com/edge-mics-start/
[7] https://www.youtube.com/watch?v=t9U5f3fh_8w
[8] https://www.aliyun.com/sswb/992721.html
