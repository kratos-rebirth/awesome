---
title: 秀秀我的站点
date: 2024-06-23 00:08:16
---
当您使用 Kratos : Rebirth 作为您站点的主题时，加入列表非常简单，只需要这样四步（全都可以在网页上完成）：

1. 注册一个 GitHub 账号（如果已经有的话可以跳过）；
2. 前往 [kratos-rebirth/awesome](https://github.com/kratos-rebirth/awesome) 仓库页面，fork 一份；
3. 将站点图片上传至 `source/images` 目录，再在 `awesome.yml` 文件里添加上您的站点信息；
4. 保存，提交，向上游开启一个 Pull request 。

这样就完成了！我们会检查您提交的信息，一切没问题的话您的站点很快就能在这里看到啦。

其中，站点信息的格式是这样的（请注意第一行最开始的减号）：

```yaml
- title: "站点名称"
  description: "站点的一句话描述"
  image: "站点的图片（或者可以是自己的头像）"
  link: "站点的地址"
```

一个填充完成的信息看起来像是这样：

```yaml
- title: "糖菓·部落"
  description: "Never drown the flame of hope"
  image: "/images/candinya.webp"
  link: "https://candinya.com"
```

当然您也可以直接在文件中找到更多其他站点的样例来参考。

如果您有问题的话欢迎随时开启一个 issue 来和我们联系，未来我们也可能会推出基于 issue 自动化的加入机制，以便尽可能地进一步简化操作流程。预祝您使用愉快！
