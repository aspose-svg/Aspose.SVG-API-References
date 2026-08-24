---
title: "Sandbox 枚举"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Sandbox 枚举。沙箱标志集是以下零个或多个标志的集合，用于限制潜在不受信任资源的能力。"
type: docs
weight: 5680
url: /zh/net/aspose.svg/sandbox/
---
## Sandbox enumeration

沙箱标志集是一组零个或多个以下标志，用于限制潜在不受信任资源的能力。

```csharp
[Flags]
public enum Sandbox
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 未设置任何标志，接受所有 sandbox 功能 |
| Navigation | `1` | 此标志阻止内容导航到除沙箱浏览上下文本身（或其内部进一步嵌套的浏览上下文）之外的浏览上下文、辅助浏览上下文（受下文定义的 sandboxed auxiliary navigation browsing context 标志保护）以及顶层浏览上下文（受下文定义的 sandboxed top-level navigation browsing context 标志保护）。如果未设置 sandboxed auxiliary navigation browsing context 标志，则在某些情况下限制仍允许打开弹出窗口（新的顶层浏览上下文）。这些浏览上下文始终拥有一个在创建该浏览上下文时设置的被允许的沙箱导航器，允许创建它们的浏览上下文实际导航它们。（否则，即使弹出窗口已打开，sandboxed navigation browsing context 标志也会阻止其被导航。） |
| AuxiliaryNavigation | `2` | 此标志阻止内容创建新的辅助浏览上下文，例如使用 target 属性或 window.open() 方法。 |
| TopLevelNavigation | `4` | 此标志阻止内容导航其顶层浏览上下文并阻止内容关闭其顶层浏览上下文。当未设置 sandboxed top-level navigation browsing context 标志时，内容可以导航其顶层浏览上下文，但其他浏览上下文仍受 sandboxed navigation browsing context 标志以及可能的 sandboxed auxiliary navigation browsing context 标志保护。 |
| Plugins | `8` | 此标志阻止内容实例化插件，无论是使用 embed 元素、object 元素、applet 元素，还是通过导航嵌套的浏览上下文，除非这些插件能够得到安全保障。 |
| Origin | `10` | 此标志将内容强制置于唯一来源，从而阻止其访问同一来源的其他内容。 |
| Forms | `20` | 此标志阻止表单提交。 |
| PointerLock | `40` | 此标志禁用 Pointer Lock API。 |
| Scripts | `80` | 此标志阻止脚本执行。 |
| AutomaticFeatures | `100` | 此标志阻止自动触发的功能，例如自动播放视频或自动聚焦表单控件。 |
| Fullscreen | `200` | 此标志阻止内容使用 requestFullscreen() 方法。 |
| DocumentDomain | `400` | 此标志阻止内容使用 document.domain 功能更改有效的脚本来源。 |
| Images | `800` | 此标志禁用图像加载。 |

### 另请参阅

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
