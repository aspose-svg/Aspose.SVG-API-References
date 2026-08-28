---
title: "DeviceTGraphicContextTRenderingOptions.PageWritingStrategyTGraphicContextTRenderingOptions 列挙型"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Rendering.Device2PageWritingStrategyTGraphicContextTRenderingOptions 列挙型。ページを出力ストリームstreamstreams に書き込むための戦略タイプを指定します。"
type: docs
weight: 4840
url: /ja/net/aspose.svg.rendering/device-2.pagewritingstrategy-2/
---
## Device<TGraphicContext,TRenderingOptions>.PageWritingStrategy<TGraphicContext,TRenderingOptions> enumeration

ページを出力ストリーム\streams に書き込むための戦略タイプを指定します。

```csharp
public enum PageWritingStrategy<TGraphicContext, TRenderingOptions>
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| SingleStream | `0` | すべてのページを1つの出力ストリームに書き込みます。 |
| MultipleStreams | `1` | 各ページをそれぞれのストリームに書き込みます。 |

### 参照

* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../device-2/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
