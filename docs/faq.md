# 常见问题

以下是文档中其他部分未回答的常见问题。

---

## 关于Synthesizer V Studio

### 我可以将Synthesizer V Studio用于商业目的吗？
是的，Basic版和Pro版都可以用于商业目的，没有收入限制。

每个歌声数据库都有单独的条款，您可以在每个歌声数据库的安装目录中找到其许可证。

Dreamtonics歌声数据库的条款可以在[Dreamtonics官网](https://dreamtonics.com/en/terms/)上找到。

### Basic版和Pro版有什么区别？

与Pro版相比，Synthesizer V Studio Basic功能有限，Basic版中受限或不可用的功能列表可以在[Synthesizer V Studio Pro](https://store.dreamtonics.com/product/editor-svstudio-pro/)的商店页面上找到。

本文档将标注需要Pro版的功能（例如在[声线参数](ai-functions/vocal-modes.md)页面上）。

### 什么是“精简版（Lite版）”歌声数据库？

精简版语音数据库是付费产品的低质量版本，可免费获得，但功能有限。

- 不支持声线参数
- 没有跨语言支持
- 音域缩小
- 低质量输出（更多噪声/伪影）
    - 精简版歌声数据库仅限于“语音”面板中的“首选速度”渲染模式
- 不太自然的音高模式

精简语音数据库受以下条款的约束：

- 您不得将精简版用于商业目的
- 您不得代表组织使用精简版发布您的作品
- 如果您希望发布使用精简版创建的作品，您必须清楚地说明所使用的歌声数据库的名称以及使用精简版的事实
- 您应该知晓，精简版并不代表同一歌声数据库的完整版本的质量，Dreamtonics对歌声数据库的精简版不作质量或数量保证。

### 什么是"FLT（功能限制版）"歌声数据库？
“功能限制版”歌声数据库是付费产品的免费版本，具有有限的功能，但它们与精简版歌声数据库的不同之处在于它们不会降低输出质量。FLT 歌声数据库主要用作开发中产品的预览版本（与精简版语音数据库相反，后者是已发布产品的受限版本）。

- 每个 FLT 声库最多有一个轨道。
- 导出：输出限制为前 45 秒。
- AI重录：仅音高重录。
- 声线参数和跨语言合成：有限的选项。
- 仅可在独立编辑器中使用。
- 仅限非商业用途。

### 我的设置保存在哪里？

设置保存在名为`settings.xml`的文件中。您可以根据您的操作系统在以下位置找到它：

|操作系统|文件位置|
|---|---|
|Windows|`Documents\Dreamtonics\Synthesizer V Studio\settings`|
|MacOS|`/Library/Application Support/Dreamtonics/settings`|
|Linux|`<your installation directory>/settings`<br/>例如：<br/>`/opt/Synthesizer V Studio Pro/settings/settings.xml`|

如果软件设置未成功保存，或者每次软件启动时都重置，这通常是因为应用程序没有访问此文件夹的适当权限。这可以通过重新安装软件或授予适当的文件权限来解决。

### “轨道管理器”在哪里？

Synthesizer V的原始版本有一个单独的窗口来管理轨道。在 Synthesizer V Studio 中，所有[管理音轨](quickstart/managing-tracks.md) 都是通过编曲栏完成的。

### 原始手册有一页“声门效果”，为什么我在这里找不到任何关于它的内容？

很遗憾，声门效果尚未在Synthesizer V Studio中实现。

## 关于本网站

### 键盘快捷键在Mac上不起作用，为什么？

Mac 的键盘布局与其他设备略有不同。一般你看到++ctrl++的地方，Mac用户通常会按++cmd++，相反，你看到的++alt++在Mac上通常是++opt++。

### 为什么有些示例在手动音高模式下音符的角落没有标志？

在 1.9.0 版之前，音高模式的处理方式不同，并且没有音符级指示器，因为 AI 生成的音高偏差（“即时模式”）是项目范围的设置。

### 如何离线访问手册？

您可以通过下面的下载链接下载手册的离线版本。您必须解压缩文件夹，然后在 Web 浏览器中打开“index.html”文件。

请记住，与在线版本不同，离线手册需要重新下载才能看到更新。这可以通过将下载最新的zip并解压缩到同一位置（覆盖旧文件）来完成。

PDF版本也可用，但由于格式的原因，它不包括视频示例或在线版具有的导航和搜索功能。

[下载](https://github.com/claire-west/svstudio-manual-zh/releases/tag/latest){ .md-button }

---

[报告问题](https://github.com/claire-west/svstudio-manual-zh/issues/new?template=report-a-problem.md&title=[Page: FAQ])