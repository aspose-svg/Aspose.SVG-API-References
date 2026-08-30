---
title: "RendererTSource klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Rendering.Renderer1TSource klass. Den grundläggande abstrakta klassen för alla renderare"
type: docs
weight: 5070
url: /sv/net/aspose.svg.rendering/renderer-1/
---
## Renderer<TSource> class

Den abstrakta basklassen för alla renderare.

```csharp
public abstract class Renderer<TSource> : Renderer
```

| Parameter | Beskrivning |
| --- | --- |
| TSource | Typen av källan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.svg.rendering/renderer/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_3)(*[IDevice](../idevice/), TSource*) | Definierar metod för att rendera *TSource* till angiven [`IDevice`](../idevice/). |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_6)(*[IDevice](../idevice/), params TSource[]*) | Definierar metod för att rendera flera *TSource*s till en specifik [`IDevice`](../idevice/). |
| abstract [Render](../../aspose.svg.rendering/renderer-1/render/#render_1)(*[IDevice](../idevice/), CancellationToken, params TSource[]*) | Definierar en metod för att rendera flera *TSource*s till en specifik [`IDevice`](../idevice/), med hjälp av en avbokningstoken för att begära avbrytning av operationen. |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render)(*[IDevice](../idevice/), int, params TSource[]*) | Definierar metod för att rendera flera *TSource*s till en specifik [`IDevice`](../idevice/). |
| abstract [Render](../../aspose.svg.rendering/renderer-1/render/#render_2)(*[IDevice](../idevice/), TimeSpan, params TSource[]*) | Definierar metod för att rendera flera *TSource*s till en specifik [`IDevice`](../idevice/). |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_4)(*[IDevice](../idevice/), TSource, int*) | Definierar metod för att rendera *TSource* till angiven [`IDevice`](../idevice/). |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_5)(*[IDevice](../idevice/), TSource, TimeSpan*) | Definierar metod för att rendera *TSource* till angiven [`IDevice`](../idevice/). |

### Se även

* class [Renderer](../renderer/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
