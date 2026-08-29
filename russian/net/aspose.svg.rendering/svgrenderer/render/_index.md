---
title: "SvgRenderer.Render"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Render класса SvgRenderer. Определяет метод для рендеринга нескольких SVGDocument в конкретный IDevice"
type: docs
weight: 20
url: /ru/net/aspose.svg.rendering/svgrenderer/render/
---
## Render(*[IDevice](../../idevice/), TimeSpan, params SVGDocument[]*) {#render_6}

Определяет метод для рендеринга нескольких [`SVGDocument`](../../../aspose.svg/svgdocument/)s в конкретный [`IDevice`](../../idevice/).

```csharp
public override void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| timeout | TimeSpan | Объект TimeSpan, представляющий количество миллисекунд ожидания, или объект TimeSpan, представляющий -1 миллисекунду для бесконечного ожидания. |
| источники | SVGDocument[] | SVG документы для рендеринга. |

### См. также

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params SVGDocument[]*) {#render_5}

Определяет метод для рендеринга нескольких [`SVGDocument`](../../../aspose.svg/svgdocument/)s в конкретный [`IDevice`](../../idevice/), используя токен отмены для запроса отмены операции.

```csharp
public override void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| cancellationToken | CancellationToken | Токен отмены, который следует отслеживать во время ожидания завершения задачи. |
| источники | SVGDocument[] | SVG документы для рендеринга. |

### См. также

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)
