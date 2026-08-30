---
title: "IPathBuilder.Build"
second_title: "Aspose.SVG för .NET API-referens"
description: "IPathBuilder Build-metoden. Optimerar en given spårning till ett SVG-sökvägssegment med så få linje- och Bézier-kurvkommandon som möjligt för exakt återgivning"
type: docs
weight: 10
url: /sv/net/aspose.svg.imagevectorization/ipathbuilder/build/
---
## IPathBuilder.Build method

Optimerar ett givet spår till ett SVG-sökvägssegment, med minsta möjliga antal linje- och Bézierkurvkommandon för en exakt representation.

```csharp
public string Build(IEnumerable<PointF> trace)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| spår | IEnumerable`1 | En sekvens av punkter som beskriver spåret som ska optimeras till en SVG-sökväg. |

### Returvärde

En sträng som representerar ett SVG-sökvägssegment, som effektivt approximerar den ursprungliga spårningen med minimala linje- och Bézier-kurvkommandon.

### Se även

* interface [IPathBuilder](../)
* namespace [Aspose.Svg.ImageVectorization](../../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../../)
