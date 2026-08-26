---
title: "ImageTraceSimplifier Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.ImageVectorization.ImageTraceSimplifier class. Die ImageTraceSimplifier class ist dafür verantwortlich, die Anzahl der Punkte in einer Kurve zu reduzieren, die durch eine Reihe von Trace-Punkten approximiert wird."
type: docs
weight: 4190
url: /de/net/aspose.svg.imagevectorization/imagetracesimplifier/
---
## ImageTraceSimplifier class

Die ImageTraceSimplifier Klasse ist dafür verantwortlich, die Anzahl der Punkte in einer Kurve zu reduzieren, die durch eine Reihe von Trace-Punkten approximiert wird.

```csharp
public class ImageTraceSimplifier : IImageTraceSimplifier
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageTraceSimplifier](imagetracesimplifier/#constructor)() | Initialisiert eine neue Instanz der `ImageTraceSimplifier`-Klasse. |
| [ImageTraceSimplifier](imagetracesimplifier/#constructor_1)(*float*) | Initialisiert eine neue Instanz der `ImageTraceSimplifier`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Tolerance](../../aspose.svg.imagevectorization/imagetracesimplifier/tolerance/) { get; set; } | Der Wert der Toleranz bestimmt die maximal zulässige Fehlertoleranz, damit ein Punkt aus der Spur entfernt werden kann. Er muss im Bereich von 0 bis 4 liegen. Höhere oder niedrigere Werte werden entsprechend an den Minimal- bzw. Maximalwert dieses Bereichs angepasst. Der Standardwert ist 0,3. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Simplify](../../aspose.svg.imagevectorization/imagetracesimplifier/simplify/)(*IEnumerable&lt;PointF&gt;*) | Reduziert die Anzahl der Punkte in der Liste der Trace-Punkte. |

### Siehe auch

* interface [IImageTraceSimplifier](../iimagetracesimplifier/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
