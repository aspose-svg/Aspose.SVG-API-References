---
title: "Класс RendererTSource"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Rendering.Renderer1TSource. Базовый абстрактный класс для всех рендереров."
type: docs
weight: 5070
url: /ru/net/aspose.svg.rendering/renderer-1/
---
## Renderer<TSource> class

Базовый абстрактный класс для всех рендереров.

```csharp
public abstract class Renderer<TSource> : Renderer
```

| Параметр | Описание |
| --- | --- |
| TSource | Тип источника. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.svg.rendering/renderer/dispose/)() | Освобождает неуправляемые и — при необходимости — управляемые ресурсы. |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_3)(*[IDevice](../idevice/), TSource*) | Определяет метод для рендеринга *TSource* в указанный [`IDevice`](../idevice/). |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_6)(*[IDevice](../idevice/), params TSource[]*) | Определяет метод для рендеринга нескольких *TSource*s в конкретный [`IDevice`](../idevice/). |
| abstract [Render](../../aspose.svg.rendering/renderer-1/render/#render_1)(*[IDevice](../idevice/), CancellationToken, params TSource[]*) | Определяет метод для рендеринга нескольких *TSource*s в конкретный [`IDevice`](../idevice/), используя токен отмены для запроса отмены операции. |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render)(*[IDevice](../idevice/), int, params TSource[]*) | Определяет метод для рендеринга нескольких *TSource*s в конкретный [`IDevice`](../idevice/). |
| abstract [Render](../../aspose.svg.rendering/renderer-1/render/#render_2)(*[IDevice](../idevice/), TimeSpan, params TSource[]*) | Определяет метод для рендеринга нескольких *TSource*s в конкретный [`IDevice`](../idevice/). |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_4)(*[IDevice](../idevice/), TSource, int*) | Определяет метод для рендеринга *TSource* в указанный [`IDevice`](../idevice/). |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_5)(*[IDevice](../idevice/), TSource, TimeSpan*) | Определяет метод для рендеринга *TSource* в указанный [`IDevice`](../idevice/). |

### См. также

* class [Renderer](../renderer/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
