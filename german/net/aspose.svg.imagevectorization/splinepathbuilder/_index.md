---
title: "SplinePathBuilder Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.ImageVectorization.SplinePathBuilder Klasse. Die SplinePathBuilder Klasse ist dafür ausgelegt, einen glatten Pfad zu erstellen, indem zentripetale Catmull‑Rom‑Splines in Bézier‑Kurven umgewandelt werden. Sie bietet eine Methode, um einen Pfad zu erzeugen, der sanft durch eine Menge von Punkten interpoliert und dabei ein Gleichgewicht zwischen Genauigkeit zu den Punkten und Glätte der Kurve bietet."
type: docs
weight: 4230
url: /de/net/aspose.svg.imagevectorization/splinepathbuilder/
---
## SplinePathBuilder class

Die `SplinePathBuilder` Klasse ist dafür ausgelegt, einen glatten Pfad zu erstellen, indem zentripetale Catmull‑Rom‑Splines in Bézier‑Kurven umgewandelt werden. Sie bietet eine Methode, um einen Pfad zu erzeugen, der sanft durch eine Menge von Punkten interpoliert und dabei ein Gleichgewicht zwischen Genauigkeit zu den Punkten und Glätte der Kurve bietet.

```csharp
public class SplinePathBuilder : IPathBuilder
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SplinePathBuilder](splinepathbuilder/#constructor)() | Initialisiert eine neue Instanz der `SplinePathBuilder` Klasse. |
| [SplinePathBuilder](splinepathbuilder/#constructor_2)(*float*) | Initialisiert eine neue Instanz der `SplinePathBuilder` Klasse. |
| [SplinePathBuilder](splinepathbuilder/#constructor_1)(*[IImageTraceSmoother](../iimagetracesmoother/), [IImageTraceSimplifier](../iimagetracesimplifier/), float*) | Initialisiert eine neue Instanz der `SplinePathBuilder` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Tension](../../aspose.svg.imagevectorization/splinepathbuilder/tension/) { get; set; } | Der Wert der Spannungen beeinflusst, wie stark die Kurve an den (interpolierten) Kontrollpunkten abknickt. Er muss im Bereich von 0 bis 1 liegen. Höhere oder niedrigere Werte werden entsprechend auf den Minimal‑ bzw. Maximalwert dieses Bereichs begrenzt. |
| [TraceSimplifier](../../aspose.svg.imagevectorization/splinepathbuilder/tracesimplifier/) { get; set; } | Liest oder setzt den Trace‑Vereinfacher. |
| [TraceSmoother](../../aspose.svg.imagevectorization/splinepathbuilder/tracesmoother/) { get; set; } | Liest oder setzt den Trace‑Glätter. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Build](../../aspose.svg.imagevectorization/splinepathbuilder/build/)(*IEnumerable&lt;PointF&gt;*) | Erstellt einen glatten Pfad durch eine Sequenz von Punkten, indem zentripetale Catmull‑Rom‑Splines in Bézier‑Kurven umgewandelt werden. Diese Methode sorgt für einen natürlichen und glatten Übergang durch jeden Punkt und erzeugt einen SVG‑Pfad, der der bereitgestellten Spur eng folgt. |

### Siehe auch

* interface [IPathBuilder](../ipathbuilder/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
