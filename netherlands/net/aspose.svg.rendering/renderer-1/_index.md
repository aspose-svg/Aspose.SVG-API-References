---
title: "RendererTSource Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Rendering.Renderer1TSource klasse. De basis‑abstracte klasse voor alle renderers"
type: docs
weight: 5070
url: /nl/net/aspose.svg.rendering/renderer-1/
---
## Renderer<TSource> class

De abstracte basisklasse voor alle renderers.

```csharp
public abstract class Renderer<TSource> : Renderer
```

| Parameter | Beschrijving |
| --- | --- |
| TSource | Het type van de bron. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../aspose.svg.rendering/renderer/dispose/)() | Vrijgeeft niet‑beheerde en - optioneel - beheerde bronnen. |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_3)(*[IDevice](../idevice/), TSource*) | Definieert methode voor het renderen van *TSource* naar het opgegeven [`IDevice`](../idevice/). |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_6)(*[IDevice](../idevice/), params TSource[]*) | Definieert methode voor het renderen van meerdere *TSource*’s naar een specifiek [`IDevice`](../idevice/). |
| abstract [Render](../../aspose.svg.rendering/renderer-1/render/#render_1)(*[IDevice](../idevice/), CancellationToken, params TSource[]*) | Definieert een methode voor het renderen van meerdere *TSource*’s naar een specifiek [`IDevice`](../idevice/), met behulp van een annulerings‑token om annulering van de bewerking aan te vragen. |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render)(*[IDevice](../idevice/), int, params TSource[]*) | Definieert methode voor het renderen van meerdere *TSource*’s naar een specifiek [`IDevice`](../idevice/). |
| abstract [Render](../../aspose.svg.rendering/renderer-1/render/#render_2)(*[IDevice](../idevice/), TimeSpan, params TSource[]*) | Definieert methode voor het renderen van meerdere *TSource*’s naar een specifiek [`IDevice`](../idevice/). |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_4)(*[IDevice](../idevice/), TSource, int*) | Definieert methode voor het renderen van *TSource* naar het opgegeven [`IDevice`](../idevice/). |
| [Render](../../aspose.svg.rendering/renderer-1/render/#render_5)(*[IDevice](../idevice/), TSource, TimeSpan*) | Definieert methode voor het renderen van *TSource* naar het opgegeven [`IDevice`](../idevice/). |

### Zie ook

* class [Renderer](../renderer/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
