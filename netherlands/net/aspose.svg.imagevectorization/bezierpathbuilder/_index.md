---
title: "BezierPathBuilder-klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.ImageVectorization.BezierPathBuilder class. De BezierPathBuilder-klasse is verantwoordelijk voor het construeren van een Bezier-pad uit een gegeven set punten. Het benadert een trace van punten met een Bezier-curve en optimaliseert het aantal segmenten om nauwkeurig overeen te komen met de originele trace, terwijl de complexiteit wordt geminimaliseerd."
type: docs
weight: 4150
url: /nl/net/aspose.svg.imagevectorization/bezierpathbuilder/
---
## BezierPathBuilder class

De `BezierPathBuilder`-klasse is verantwoordelijk voor het construeren van een Bezier-pad uit een gegeven set punten. Het benadert een trace van punten met een Bezier-curve, optimaliseert het aantal segmenten om nauwkeurig overeen te komen met de originele trace, terwijl de complexiteit wordt geminimaliseerd.

```csharp
public class BezierPathBuilder : IPathBuilder
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [BezierPathBuilder](bezierpathbuilder/)() | Initialiseert een nieuw exemplaar van de `BezierPathBuilder`-klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ErrorThreshold](../../aspose.svg.imagevectorization/bezierpathbuilder/errorthreshold/) { get; set; } | Haalt of stelt de foutdrempel in. Deze parameter definieert de maximale afwijking van punten ten opzichte van de aangepaste curve. Standaard is deze 30. |
| [MaxIterations](../../aspose.svg.imagevectorization/bezierpathbuilder/maxiterations/) { get; set; } | Haalt of stelt de foutdrempel in. Deze parameter definieert het aantal iteraties voor de kleinste-kwadraten benaderingsmethode. Standaard is deze 30. |
| [TraceSmoother](../../aspose.svg.imagevectorization/bezierpathbuilder/tracesmoother/) { get; set; } | Haalt of stelt de trace smoother in. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Build](../../aspose.svg.imagevectorization/bezierpathbuilder/build/)(*IEnumerable&lt;PointF&gt;*) | Construeert een geoptimaliseerd Bezier-pad uit een reeks trace-punten. De methode benadert de gegeven trace met een Bezier-curve, gebruikmakend van een combinatie van lijn- en curve-segmenten. Het streeft ernaar het aantal segmenten te minimaliseren terwijl het pad nauwkeurig aansluit op de originele trace. |

### Zie ook

* interface [IPathBuilder](../ipathbuilder/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
