---
title: "BezierPathBuilder.Build"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "BezierPathBuilder Build-methode. Bouwt een geoptimaliseerd Bezier-pad op basis van een reeks trace-punten. De methode benadert de gegeven trace met een Bezier-kromme door een combinatie van lijn- en krommesegmenten te gebruiken. Het streeft ernaar het aantal segmenten te minimaliseren terwijl het pad nauw aansluit bij de oorspronkelijke trace."
type: docs
weight: 50
url: /nl/net/aspose.svg.imagevectorization/bezierpathbuilder/build/
---
## BezierPathBuilder.Build method

Construeert een geoptimaliseerd Bezier-pad uit een reeks trace-punten. De methode benadert de gegeven trace met een Bezier-curve, gebruikmakend van een combinatie van lijn- en curve-segmenten. Het streeft ernaar het aantal segmenten te minimaliseren terwijl het pad nauwkeurig aansluit op de originele trace.

```csharp
public string Build(IEnumerable<PointF> trace)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| trace | IEnumerable`1 | De reeks punten die de te benaderen trace definiëren. |

### Retourwaarde

Een tekenreeks die de SVG-padgegevens vertegenwoordigt. Deze gegevens bestaan uit een reeks commando's en coördinaten die het Bezier-pad definiëren, waarbij de invoertrace nauwkeurig wordt benaderd met minimale complexiteit.

### Zie ook

* class [BezierPathBuilder](../)
* namespace [Aspose.Svg.ImageVectorization](../../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../../)
