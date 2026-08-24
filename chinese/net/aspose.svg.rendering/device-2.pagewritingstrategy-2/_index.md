---
title: "DeviceTGraphicContextTRenderingOptions.PageWritingStrategyTGraphicContextTRenderingOptions Enum"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Rendering.Device2PageWritingStrategyTGraphicContextTRenderingOptions 枚举。指定将页面写入输出流的策略类型。"
type: docs
weight: 4840
url: /zh/net/aspose.svg.rendering/device-2.pagewritingstrategy-2/
---
## Device<TGraphicContext,TRenderingOptions>.PageWritingStrategy<TGraphicContext,TRenderingOptions> enumeration

指定将页面写入输出流\streams 的策略类型。

```csharp
public enum PageWritingStrategy<TGraphicContext, TRenderingOptions>
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| SingleStream | `0` | 将所有页面写入一个输出流。 |
| MultipleStreams | `1` | 将每个页面写入各自的流。 |

### 另请参阅

* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../device-2/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
