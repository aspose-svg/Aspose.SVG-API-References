---
title: "BezierPathBuilder.Build"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "BezierPathBuilder Build-Methode. Erstellt einen optimierten Bezier-Pfad aus einer Sequenz von Trace-Punkten. Die Methode approximiert den gegebenen Trace mit einer Bezier-Kurve unter Verwendung einer Kombination aus Geraden- und Kurvensegmenten. Sie zielt darauf ab, die Anzahl der Segmente zu minimieren und gleichzeitig sicherzustellen, dass der Pfad den ursprünglichen Trace eng nachbildet."
type: docs
weight: 50
url: /de/net/aspose.svg.imagevectorization/bezierpathbuilder/build/
---
## BezierPathBuilder.Build method

Erstellt einen optimierten Bézier-Pfad aus einer Sequenz von Trace-Punkten. Die Methode approximiert den gegebenen Trace mit einer Bézier-Kurve und verwendet dabei eine Kombination aus Linien- und Kurvensegmenten. Sie zielt darauf ab, die Anzahl der Segmente zu minimieren, während der Pfad den ursprünglichen Trace eng anpasst.

```csharp
public string Build(IEnumerable<PointF> trace)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Spur | IEnumerable`1 | Die Sequenz von Punkten, die den zu approximierenden Trace definieren. |

### Rückgabewert

Eine Zeichenkette, die die SVG-Pfaddaten darstellt. Diese Daten bestehen aus einer Reihe von Befehlen und Koordinaten, die den Bezier-Pfad definieren und den Eingabe-Trace mit minimaler Komplexität genau approximieren.

### Siehe auch

* class [BezierPathBuilder](../)
* namespace [Aspose.Svg.ImageVectorization](../../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../../)
