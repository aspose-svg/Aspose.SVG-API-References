---
title: "RendererTSource-Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Rendering.Renderer1TSource-Klasse. Die abstrakte Basisklasse für alle Renderer."
type: docs
weight: 5070
url: /de/net/aspose.svg.rendering/renderer-1/
---
## Renderer<TSource> class

Die abstrakte Basisklasse für alle Renderer.

```csharp
public abstract class Renderer<TSource> : Renderer
```

| Parameter | Beschreibung |
| --- | --- |
| TSource | Der Typ der Quelle. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.svg.rendering/renderer/dispose/)() | Gibt nicht verwaltete und – optional – verwaltete Ressourcen frei. |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_3)(*[IDevice](../idevice/), TSource*) | Definiert eine Methode zum Rendern von *TSource* in das angegebene [`IDevice`](../idevice/). |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_6)(*[IDevice](../idevice/), params TSource[]*) | Definiert eine Methode zum Rendern mehrerer *TSource*s in ein bestimmtes [`IDevice`](../idevice/). |
| abstract [Render](../../aspose.svg.rendering/renderer-1/render/#render_1)(*[IDevice](../idevice/), CancellationToken, params TSource[]*) | Definiert eine Methode zum Rendern mehrerer *TSource*s in ein bestimmtes [`IDevice`](../idevice/), wobei ein Cancellation‑Token verwendet wird, um die Abbruchanforderung für den Vorgang zu stellen. |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render)(*[IDevice](../idevice/), int, params TSource[]*) | Definiert eine Methode zum Rendern mehrerer *TSource*s in ein bestimmtes [`IDevice`](../idevice/). |
| abstract [Render](../../aspose.svg.rendering/renderer-1/render/#render_2)(*[IDevice](../idevice/), TimeSpan, params TSource[]*) | Definiert eine Methode zum Rendern mehrerer *TSource*s in ein bestimmtes [`IDevice`](../idevice/). |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_4)(*[IDevice](../idevice/), TSource, int*) | Definiert eine Methode zum Rendern von *TSource* in das angegebene [`IDevice`](../idevice/). |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_5)(*[IDevice](../idevice/), TSource, TimeSpan*) | Definiert eine Methode zum Rendern von *TSource* in das angegebene [`IDevice`](../idevice/). |

### Siehe auch

* class [Renderer](../renderer/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
