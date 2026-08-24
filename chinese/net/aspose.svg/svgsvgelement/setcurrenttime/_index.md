---
title: "SVGSVGElement.SetCurrentTime"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGSVGElement SetCurrentTime 方法。调整此 SVG 文档片段的时钟以建立新的当前时间。如果在文档时间线开始之前调用 setCurrentTime，例如在 script 元素中的脚本在文档的 SVGLoad 事件分发之前运行，则该方法最后一次调用中的 seconds 值表示文档时间线开始后文档将跳转到的时间。"
type: docs
weight: 230
url: /zh/net/aspose.svg/svgsvgelement/setcurrenttime/
---
## SVGSVGElement.SetCurrentTime method

调整此 SVG 文档片段的时钟，设定新的当前时间。如果在文档时间线开始之前调用 setCurrentTime（例如，在文档的 SVGLoad 事件分发之前，由 ‘script’ 元素中的脚本运行），则该方法上一次调用中的 seconds 值表示文档时间线开始后文档将跳转到的时间。

```csharp
public void SetCurrentTime(float seconds)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 秒 | Single | 相对于当前 SVG 文档片段的起始时间的新当前时间（秒）。 |

### 另请参阅

* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
