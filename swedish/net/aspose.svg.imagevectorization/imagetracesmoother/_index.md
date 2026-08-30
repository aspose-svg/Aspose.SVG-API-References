---
title: "ImageTraceSmoother‑klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.ImageVectorization.ImageTraceSmoother‑klass. ImageTraceSimplifier‑klassen ansvarar för att jämna ut antalet punkter i en kurva som approximeras av en serie spårpunkter. Denna klass implementerar närmaste-granne‑metoden."
type: docs
weight: 4200
url: /sv/net/aspose.svg.imagevectorization/imagetracesmoother/
---
## ImageTraceSmoother class

Klassen ImageTraceSimplifier ansvarar för att jämna ut antalet punkter i en kurva som approximeras av en serie spårpunkter. Denna klass implementerar närmaste-granne-metoden.

```csharp
public class ImageTraceSmoother : IImageTraceSmoother
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageTraceSmoother](imagetracesmoother/#constructor)() | Initierar en ny instans av klassen `ImageTraceSmoother`. |
| [ImageTraceSmoother](imagetracesmoother/#constructor_1)(*int*) | Initierar en ny instans av klassen `ImageTraceSmoother`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Extent](../../aspose.svg.imagevectorization/imagetracesmoother/extent/) { get; set; } | Hämtar eller anger omfattningen av regionen som beaktas av frågepunkten. Den måste ligga i intervallet 1 till 20. Alla högre eller lägre värden justeras till respektive minimi- och maximivärde i detta intervall. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [Smooth](../../aspose.svg.imagevectorization/imagetracesmoother/smooth/)(*IEnumerable&lt;PointF&gt;*) | Jämnar ut spåret. |

### Se även

* interface [IImageTraceSmoother](../iimagetracesmoother/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
