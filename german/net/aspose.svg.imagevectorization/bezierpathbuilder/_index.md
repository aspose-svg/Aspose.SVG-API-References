---
title: "BezierPathBuilder Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.ImageVectorization.BezierPathBuilder Klasse. Die BezierPathBuilder Klasse ist für die Konstruktion eines Bézier-Pfads aus einem gegebenen Satz von Punkten verantwortlich. Sie approximiert einen Trace von Punkten mit einer Bézier-Kurve und optimiert die Anzahl der Segmente, um den ursprünglichen Trace möglichst genau zu treffen, während die Komplexität minimiert wird."
type: docs
weight: 4150
url: /de/net/aspose.svg.imagevectorization/bezierpathbuilder/
---
## BezierPathBuilder class

Die `BezierPathBuilder` Klasse ist für die Konstruktion eines Bézier-Pfads aus einem gegebenen Satz von Punkten verantwortlich. Sie approximiert einen Trace von Punkten mit einer Bézier-Kurve, optimiert die Anzahl der Segmente, um den ursprünglichen Trace möglichst genau zu treffen, während die Komplexität minimiert wird.

```csharp
public class BezierPathBuilder : IPathBuilder
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [BezierPathBuilder](bezierpathbuilder/)() | Initialisiert eine neue Instanz der `BezierPathBuilder` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ErrorThreshold](../../aspose.svg.imagevectorization/bezierpathbuilder/errorthreshold/) { get; set; } | Liest oder setzt die Fehlerschwelle. Dieser Parameter definiert die maximale Abweichung der Punkte von der angepassten Kurve. Standardmäßig ist er 30. |
| [MaxIterations](../../aspose.svg.imagevectorization/bezierpathbuilder/maxiterations/) { get; set; } | Liest oder setzt die Fehlerschwelle. Dieser Parameter definiert die Anzahl der Iterationen für das Kleinste-Quadrate-Approximationsverfahren. Standardmäßig ist er 30. |
| [TraceSmoother](../../aspose.svg.imagevectorization/bezierpathbuilder/tracesmoother/) { get; set; } | Liest oder setzt den Trace‑Glätter. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Build](../../aspose.svg.imagevectorization/bezierpathbuilder/build/)(*IEnumerable&lt;PointF&gt;*) | Erstellt einen optimierten Bézier-Pfad aus einer Sequenz von Trace-Punkten. Die Methode approximiert den gegebenen Trace mit einer Bézier-Kurve und verwendet dabei eine Kombination aus Linien- und Kurvensegmenten. Sie zielt darauf ab, die Anzahl der Segmente zu minimieren, während der Pfad den ursprünglichen Trace eng anpasst. |

### Siehe auch

* interface [IPathBuilder](../ipathbuilder/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
