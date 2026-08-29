---
title: "ImageTraceSmoother-klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.ImageVectorization.ImageTraceSmoother class. De ImageTraceSimplifier‑klasse is verantwoordelijk voor het gladstrijken van het aantal punten in een curve die wordt benaderd door een reeks traceerpunt(en). Deze klasse implementeert een nearest‑neighbor‑benadering."
type: docs
weight: 4200
url: /nl/net/aspose.svg.imagevectorization/imagetracesmoother/
---
## ImageTraceSmoother class

De ImageTraceSimplifier‑klasse is verantwoordelijk voor het gladstrijken van het aantal punten in een curve die wordt benaderd door een reeks traceerpunt­en. Deze klasse implementeert een nearest‑neighbor‑benadering.

```csharp
public class ImageTraceSmoother : IImageTraceSmoother
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ImageTraceSmoother](imagetracesmoother/#constructor)() | Initialiseert een nieuw exemplaar van de `ImageTraceSmoother`-klasse. |
| [ImageTraceSmoother](imagetracesmoother/#constructor_1)(*int*) | Initialiseert een nieuw exemplaar van de `ImageTraceSmoother`-klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Extent](../../aspose.svg.imagevectorization/imagetracesmoother/extent/) { get; set; } | Haalt op of stelt de omvang van het gebied in dat wordt beschouwd door het query‑punt. Het moet binnen het bereik van 1 tot 20 liggen. Hogere of lagere waarden worden respectievelijk aangepast aan de minimum‑ en maximumwaarden van dit bereik. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [Smooth](../../aspose.svg.imagevectorization/imagetracesmoother/smooth/)(*IEnumerable&lt;PointF&gt;*) | Gladstrijkt de trace. |

### Zie ook

* interface [IImageTraceSmoother](../iimagetracesmoother/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
