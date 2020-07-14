title: SimPad Nano 隐藏的灯光模式
author: Handle
lang: zh-CN
date: 2020-07-05 01:02:26
tags:
---
你有SimPad Nano吗？

如果你有一台这样的设备，你可能不知道，其实这款设备一直有一个隐藏的灯光模式。

通过以下这些步骤，你可以尝试启用。（不稳定）

<!-- more -->

1. 下载 SimPad 设置工具
2. 在设置工具中找到以下目录 `\resources\app\app\devices\simpadnano`
3. 打开`script.js`，转到第 1170 行附近的`// animeLights()`
4. 删除该行的 `//`
5. 保存

这样就已经成功恢复了被屏蔽的灯光模式，但如何使用呢？

1. 使用设置工具，将设备的灯光模式设置为 常亮
2. 重新启动设置工具，并连接设备
3. 来点音乐！

祝您玩的开心