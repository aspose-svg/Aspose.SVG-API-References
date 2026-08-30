---
title: "ImageTraceSimplifier‑klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.ImageVectorization.ImageTraceSimplifier‑klass. ImageTraceSimplifier‑klassen ansvarar för att reducera antalet punkter i en kurva som approximeras av en serie spårpunkter."
type: docs
weight: 4190
url: /sv/net/aspose.svg.imagevectorization/imagetracesimplifier/
---
## ImageTraceSimplifier class

Klassen ImageTraceSimplifier ansvarar för att minska antalet punkter i en kurva som approximeras av en serie spårpunkter.

```csharp
public class ImageTraceSimplifier : IImageTraceSimplifier
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageTraceSimplifier](imagetracesimplifier/#constructor)() | Initierar en ny instans av klassen `ImageTraceSimplifier`. |
| [ImageTraceSimplifier](imagetracesimplifier/#constructor_1)(*float*) | Initierar en ny instans av klassen `ImageTraceSimplifier`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Tolerance](../../aspose.svg.imagevectorization/imagetracesimplifier/tolerance/) { get; set; } | Värdet på toleransen bestämmer den maximala felmarginal som tillåts för en punkt att elimineras från spårningen. Det måste ligga i intervallet från 0 till 4. Alla högre eller lägre värden kommer att justeras till minimum- och maximumvärdena i detta intervall, enligt detta. Standardvärdet är 0,3. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Simplify](../../aspose.svg.imagevectorization/imagetracesimplifier/simplify/)(*IEnumerable&lt;PointF&gt;*) | Minskar antalet punkter i listan över spårningspunkterna. |

### Se även

* interface [IImageTraceSimplifier](../iimagetracesimplifier/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
