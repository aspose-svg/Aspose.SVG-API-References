---
title: "SVGBuilderExtensions.Points"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions Points‑methode. Stelt het points‑attribuut in voor een SVG‑element met behulp van een array van doubles."
type: docs
weight: 1910
url: /nl/net/aspose.svg.builder/svgbuilderextensions/points/
---
## Points<TBuilder>(*this TBuilder, params double[]*) {#points}

Stelt het 'points'‑attribuut in voor een SVG‑element met behulp van een array van doubles.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params double[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| points | Een array van doubles die de punten vertegenwoordigt (moet een even aantal zijn). |

### Retourwaarde

De builder‑instantie voor chaining.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| ArgumentException | Wordt gegooid als een oneven aantal punten wordt opgegeven. |

### Zie ook

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Points<TBuilder>(*this TBuilder, params PointF[]*) {#points_1}

Stelt het 'points'‑attribuut in voor een SVG‑element met behulp van een array van PointF‑objecten.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params PointF[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| points | Een array van PointF‑objecten die de punten vertegenwoordigen. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
