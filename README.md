# AnimeCDN 简介

使用Github提供的存储服务来存储番剧并为 [maware](https://maware.cc) 提供服务。

## 使用方法

> https://raw.githubusercontent.com/weclont/{对应的AnimeCDN节点}/master/{多层目录}/video.m3u8

对应参数可在 [目录表](https://github.com/weclont/AnimeCDN/blob/master/index.md) 中查询到。

示例：

因为源地址被墙，只有在使用梯子时可直接访问源地址。

不翻墙的情况下访问源地址需要使用代理，请自行Google或者用自己的代理来访问。

### 注意事项

Github项目库空间大小存在限制。[详见官方文档](https://docs.github.com/cn/repositories/working-with-files/managing-large-files/about-large-files-on-github)

>我们建议每个仓库均保持在 1GB 以下。 仓库的硬限制为 100GB。 如果达到 75GB，推送时您将在终端收到 Git 的警告。 如果将大文件留在仓库之外，则此限制很容易保持。 如果仓库超过 1GB，您可能会收到来自 GitHub 支持的礼貌电子邮件，要求您减小仓库的大小以使其恢复。

因此，我们将会使用更多的库来满足空间需求（您将会在我的个人库中看到AnimeCDN1,~2,~3甚至更多的库），并且您将看到所有超过50M的大文件都被拆分成多个文件储存在库中，你可能需要调整您的程序逻辑来适配这种规则。

## AnimeCDN 分节点

 - [AnimeCDN1](https://github.com/weclont/AnimeCDN1)

