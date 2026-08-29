---
title: "DeviceTGraphicContextTRenderingOptions.PageWritingStrategyTGraphicContextTRenderingOptions Enum"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Rendering.Device2PageWritingStrategyTGraphicContextTRenderingOptions enum. Указывает типы стратегий для записи страниц в потоки вывода."
type: docs
weight: 4840
url: /ru/net/aspose.svg.rendering/device-2.pagewritingstrategy-2/
---
## Device<TGraphicContext,TRenderingOptions>.PageWritingStrategy<TGraphicContext,TRenderingOptions> enumeration

Указывает типы стратегий для записи страниц в поток\потоки вывода.

```csharp
public enum PageWritingStrategy<TGraphicContext, TRenderingOptions>
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| SingleStream | `0` | Записывает все страницы в один поток вывода. |
| MultipleStreams | `1` | Записывает каждую страницу в отдельный поток. |

### См. также

* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../device-2/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
