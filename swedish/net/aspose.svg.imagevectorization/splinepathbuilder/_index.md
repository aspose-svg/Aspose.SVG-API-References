---
title: "SplinePathBuilder‑klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.ImageVectorization.SplinePathBuilder‑klass. SplinePathBuilder‑klassen är utformad för att konstruera en jämn bana genom att omvandla centripetala Catmull‑Rom‑splines till Bézier‑kurvor. Den erbjuder en metod för att generera en bana som jämnt interpolerar genom en uppsättning punkter och ger en balans mellan noggrannhet mot punkterna och kurvans släthet."
type: docs
weight: 4230
url: /sv/net/aspose.svg.imagevectorization/splinepathbuilder/
---
## SplinePathBuilder class

Klassen `SplinePathBuilder` är utformad för att konstruera en jämn bana genom att omvandla centripetala Catmull‑Rom‑splines till Bézier‑kurvor. Den erbjuder en metod för att generera en bana som jämnt interpolerar genom en uppsättning punkter, vilket ger en balans mellan noggrannhet mot punkterna och kurvans släthet.

```csharp
public class SplinePathBuilder : IPathBuilder
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SplinePathBuilder](splinepathbuilder/#constructor)() | Initierar en ny instans av klassen `SplinePathBuilder`. |
| [SplinePathBuilder](splinepathbuilder/#constructor_2)(*float*) | Initierar en ny instans av klassen `SplinePathBuilder`. |
| [SplinePathBuilder](splinepathbuilder/#constructor_1)(*[IImageTraceSmoother](../iimagetracesmoother/), [IImageTraceSimplifier](../iimagetracesimplifier/), float*) | Initierar en ny instans av klassen `SplinePathBuilder`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Tension](../../aspose.svg.imagevectorization/splinepathbuilder/tension/) { get; set; } | Värdet på spänningarna påverkar hur skarpt kurvan böjer sig vid de (interpolerade) kontrollpunkterna. Det måste ligga i intervallet 0 till 1. Alla högre eller lägre värden kommer att justeras till respektive minimum- respektive maximumvärde i detta intervall. |
| [TraceSimplifier](../../aspose.svg.imagevectorization/splinepathbuilder/tracesimplifier/) { get; set; } | Hämtar eller anger spårförenkling. |
| [TraceSmoother](../../aspose.svg.imagevectorization/splinepathbuilder/tracesmoother/) { get; set; } | Hämtar eller anger spårutjämning. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Build](../../aspose.svg.imagevectorization/splinepathbuilder/build/)(*IEnumerable&lt;PointF&gt;*) | Konstruerar en jämn bana genom en sekvens av punkter genom att konvertera centripetala Catmull‑Rom‑splines till Bézier‑kurvor. Denna metod säkerställer en naturlig och jämn övergång genom varje punkt och skapar en SVG‑bana som noggrant följer det angivna spåret. |

### Se även

* interface [IPathBuilder](../ipathbuilder/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
