---
title: "SplinePathBuilder.Build"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SplinePathBuilder Build-Methode. Konstruiert einen glatten Pfad durch eine Reihe von Punkten, indem zentripetale CatmullRom Splines in Bézier-Kurven umgewandelt werden. Diese Methode sorgt für einen natürlichen und glatten Übergang durch jeden Punkt und erstellt einen SVG-Pfad, der der bereitgestellten Spur genau folgt."
type: docs
weight: 50
url: /de/net/aspose.svg.imagevectorization/splinepathbuilder/build/
---
## SplinePathBuilder.Build method

Erstellt einen glatten Pfad durch eine Sequenz von Punkten, indem zentripetale Catmull‑Rom‑Splines in Bézier‑Kurven umgewandelt werden. Diese Methode sorgt für einen natürlichen und glatten Übergang durch jeden Punkt und erzeugt einen SVG‑Pfad, der der bereitgestellten Spur eng folgt.

```csharp
public string Build(IEnumerable<PointF> trace)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Spur | IEnumerable`1 | Die Sequenz von Punkten, die zu einem glatten Pfad interpoliert werden soll. |

### Rückgabewert

Ein String, der die SVG-Pfaddaten darstellt und Bézier-Kurvenbefehle sowie Koordinaten enthält, die die zentripetale Catmull–Rom‑Spline annähern.

### Siehe auch

* class [SplinePathBuilder](../)
* namespace [Aspose.Svg.ImageVectorization](../../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../../)
