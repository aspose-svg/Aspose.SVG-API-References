---
title: "SplinePathBuilder.Build"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SplinePathBuilder Build method. Construeert een vloeiend pad door een reeks punten door het omzetten van Centripetal CatmullRom-splines naar Bezier curves. Deze methode zorgt voor een natuurlijke en soepele overgang bij elk punt en creëert een SVG-pad dat nauwkeurig de opgegeven trace volgt."
type: docs
weight: 50
url: /nl/net/aspose.svg.imagevectorization/splinepathbuilder/build/
---
## SplinePathBuilder.Build method

Construeert een glad pad door een reeks punten door Centripetal Catmull–Rom splines om te zetten in Bezier-curves. Deze methode zorgt voor een natuurlijke en vloeiende overgang bij elk punt, en creëert een SVG-pad dat nauwkeurig de opgegeven trace volgt.

```csharp
public string Build(IEnumerable<PointF> trace)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| trace | IEnumerable`1 | De reeks punten die moeten worden geïnterpoleerd tot een vloeiend pad. |

### Retourwaarde

Een string die de SVG path data vertegenwoordigt, bestaande uit Bezier curve-commando's en coördinaten die de Centripetal Catmull–Rom spline benaderen.

### Zie ook

* class [SplinePathBuilder](../)
* namespace [Aspose.Svg.ImageVectorization](../../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../../)
