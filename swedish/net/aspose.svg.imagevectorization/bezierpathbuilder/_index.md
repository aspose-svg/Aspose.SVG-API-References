---
title: "BezierPathBuilder‑klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.ImageVectorization.BezierPathBuilder‑klass. BezierPathBuilder‑klassen ansvarar för att konstruera en Bézier‑bana från en given uppsättning punkter. Den approximerar ett spår av punkter med en Bézier‑kurva och optimerar antalet segment för att noggrant matcha det ursprungliga spåret samtidigt som komplexiteten minimeras"
type: docs
weight: 4150
url: /sv/net/aspose.svg.imagevectorization/bezierpathbuilder/
---
## BezierPathBuilder class

Klassen `BezierPathBuilder` ansvarar för att konstruera en Bézier‑bana från en given uppsättning punkter. Den approximerar ett spår av punkter med en Bézier‑kurva och optimerar antalet segment för att noggrant matcha det ursprungliga spåret samtidigt som komplexiteten minimeras.

```csharp
public class BezierPathBuilder : IPathBuilder
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [BezierPathBuilder](bezierpathbuilder/)() | Initierar en ny instans av klassen `BezierPathBuilder`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ErrorThreshold](../../aspose.svg.imagevectorization/bezierpathbuilder/errorthreshold/) { get; set; } | Hämtar eller anger feltröskeln. Denna parameter definierar maximal avvikelse för punkter från den anpassade kurvan. Standardvärdet är 30. |
| [MaxIterations](../../aspose.svg.imagevectorization/bezierpathbuilder/maxiterations/) { get; set; } | Hämtar eller anger feltröskeln. Denna parameter definierar antalet iterationer för minsta‑kvadrat‑approximeringsmetoden. Standardvärdet är 30. |
| [TraceSmoother](../../aspose.svg.imagevectorization/bezierpathbuilder/tracesmoother/) { get; set; } | Hämtar eller anger spårutjämning. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Build](../../aspose.svg.imagevectorization/bezierpathbuilder/build/)(*IEnumerable&lt;PointF&gt;*) | Bygger en optimerad Bézier-sökväg från en sekvens av spårpunkter. Metoden approximerar den givna spåret med en Bézier-kurva, med en kombination av linje- och kurvsegment. Den syftar till att minimera antalet segment samtidigt som den säkerställer att sökvägen noggrant följer det ursprungliga spåret. |

### Se även

* interface [IPathBuilder](../ipathbuilder/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
