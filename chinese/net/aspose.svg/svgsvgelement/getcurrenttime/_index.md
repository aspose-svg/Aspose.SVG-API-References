---
title: "SVGSVGElement.GetCurrentTime"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGSVGElement GetCurrentTime 方法。返回相对于当前 SVG 文档片段起始时间的当前时间（秒）。如果在文档时间线开始之前调用 getCurrentTime，例如在 script 元素中的脚本在文档的 SVGLoad 事件分发之前运行，则返回 0。"
type: docs
weight: 200
url: /zh/net/aspose.svg/svgsvgelement/getcurrenttime/
---
## SVGSVGElement.GetCurrentTime method

返回相对于当前 SVG 文档片段起始时间的当前时间（秒）。如果在文档时间线开始之前调用 getCurrentTime（例如，在文档的 SVGLoad 事件分发之前，由 ‘script’ 元素中的脚本运行），则返回 0。

```csharp
public float GetCurrentTime()
```

### 返回值

当前时间（秒），如果文档时间线尚未开始则为 0。

### 另请参阅

* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
