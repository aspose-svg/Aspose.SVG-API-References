---
title: "ImageTraceSmoother Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.ImageVectorization.ImageTraceSmoother class. Die ImageTraceSimplifier class ist dafür verantwortlich, die Anzahl der Punkte in einer Kurve zu glätten, die durch eine Reihe von Trace-Punkten approximiert wird. Diese Klasse implementiert den Ansatz des nächsten Nachbarn."
type: docs
weight: 4200
url: /de/net/aspose.svg.imagevectorization/imagetracesmoother/
---
## ImageTraceSmoother class

Die ImageTraceSimplifier Klasse ist dafür verantwortlich, die Anzahl der Punkte in einer Kurve zu glätten, die durch eine Reihe von Trace-Punkten approximiert wird. Diese Klasse implementiert einen Nearest‑Neighbor‑Ansatz.

```csharp
public class ImageTraceSmoother : IImageTraceSmoother
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageTraceSmoother](imagetracesmoother/#constructor)() | Initialisiert eine neue Instanz der `ImageTraceSmoother`-Klasse. |
| [ImageTraceSmoother](imagetracesmoother/#constructor_1)(*int*) | Initialisiert eine neue Instanz der `ImageTraceSmoother`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Extent](../../aspose.svg.imagevectorization/imagetracesmoother/extent/) { get; set; } | Ruft den Umfang der Region ab oder legt ihn fest, die vom Abfragepunkt berücksichtigt wird. Er muss im Bereich von 1 bis 20 liegen. Höhere oder niedrigere Werte werden entsprechend an den Minimal- bzw. Maximalwert dieses Bereichs angepasst. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Smooth](../../aspose.svg.imagevectorization/imagetracesmoother/smooth/)(*IEnumerable&lt;PointF&gt;*) | Glättet die Spur. |

### Siehe auch

* interface [IImageTraceSmoother](../iimagetracesmoother/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
