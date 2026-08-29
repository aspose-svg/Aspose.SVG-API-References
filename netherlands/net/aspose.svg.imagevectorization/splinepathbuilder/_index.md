---
title: "SplinePathBuilder‑klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.ImageVectorization.SplinePathBuilder‑klasse. De SplinePathBuilder‑klasse is ontworpen om een glad pad te construeren door Centripetal CatmullRom‑splines om te zetten in Bézier‑curven. Het biedt een methode om een pad te genereren dat soepel interpoleert door een reeks punten, waardoor een balans ontstaat tussen nauwkeurigheid van de punten en de gladheid van de curve."
type: docs
weight: 4230
url: /nl/net/aspose.svg.imagevectorization/splinepathbuilder/
---
## SplinePathBuilder class

De `SplinePathBuilder`‑klasse is ontworpen om een glad pad te construeren door Centripetal Catmull–Rom‑splines om te zetten in Bézier‑curven. Het biedt een methode om een pad te genereren dat soepel interpoleert door een reeks punten, waardoor een balans ontstaat tussen nauwkeurigheid van de punten en de gladheid van de curve.

```csharp
public class SplinePathBuilder : IPathBuilder
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SplinePathBuilder](splinepathbuilder/#constructor)() | Initialiseert een nieuw exemplaar van de `SplinePathBuilder`‑klasse. |
| [SplinePathBuilder](splinepathbuilder/#constructor_2)(*float*) | Initialiseert een nieuw exemplaar van de `SplinePathBuilder`‑klasse. |
| [SplinePathBuilder](splinepathbuilder/#constructor_1)(*[IImageTraceSmoother](../iimagetracesmoother/), [IImageTraceSimplifier](../iimagetracesimplifier/), float*) | Initialiseert een nieuw exemplaar van de `SplinePathBuilder`‑klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Tension](../../aspose.svg.imagevectorization/splinepathbuilder/tension/) { get; set; } | De waarde van de spanningen beïnvloedt hoe scherp de curve buigt bij de (geïnterpoleerde) controlepunten. Deze moet binnen het bereik van 0 tot 1 liggen. Hogere of lagere waarden worden respectievelijk afgestemd op de minimum- en maximumwaarden van dit bereik. |
| [TraceSimplifier](../../aspose.svg.imagevectorization/splinepathbuilder/tracesimplifier/) { get; set; } | Haalt of stelt de trace simplifier in. |
| [TraceSmoother](../../aspose.svg.imagevectorization/splinepathbuilder/tracesmoother/) { get; set; } | Haalt of stelt de trace smoother in. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Build](../../aspose.svg.imagevectorization/splinepathbuilder/build/)(*IEnumerable&lt;PointF&gt;*) | Construeert een glad pad door een reeks punten door Centripetal Catmull–Rom splines om te zetten in Bezier-curves. Deze methode zorgt voor een natuurlijke en vloeiende overgang bij elk punt, en creëert een SVG-pad dat nauwkeurig de opgegeven trace volgt. |

### Zie ook

* interface [IPathBuilder](../ipathbuilder/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
