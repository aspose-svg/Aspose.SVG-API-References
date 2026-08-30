---
title: "BezierPathBuilder.Build"
second_title: "Aspose.SVG för .NET API-referens"
description: "BezierPathBuilder Build‑metod. Bygger en optimerad Bezier‑sökväg från en sekvens av spårpunkter. Metoden approximerar det givna spåret med en Bezier‑kurva genom en kombination av linje‑ och kurvsegment. Den syftar till att minimera antalet segment samtidigt som den säkerställer att sökvägen noggrant följer det ursprungliga spåret."
type: docs
weight: 50
url: /sv/net/aspose.svg.imagevectorization/bezierpathbuilder/build/
---
## BezierPathBuilder.Build method

Bygger en optimerad Bézier-sökväg från en sekvens av spårpunkter. Metoden approximerar den givna spåret med en Bézier-kurva, med en kombination av linje- och kurvsegment. Den syftar till att minimera antalet segment samtidigt som den säkerställer att sökvägen noggrant följer det ursprungliga spåret.

```csharp
public string Build(IEnumerable<PointF> trace)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| spår | IEnumerable`1 | Sekvensen av punkter som definierar spåret som ska approximeras. |

### Returvärde

En sträng som representerar SVG‑sökvägsdata. Dessa data består av en serie kommandon och koordinater som definierar Bezier‑sökvägen, och approximerar ingångsspåret noggrant med minimerad komplexitet.

### Se även

* class [BezierPathBuilder](../)
* namespace [Aspose.Svg.ImageVectorization](../../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../../)
