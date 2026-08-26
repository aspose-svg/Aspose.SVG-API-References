---
title: "SVGBuilderExtensions.Points"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions Points-Methode. Setzt das points-Attribut für ein SVG-Element mithilfe eines Arrays von Doubles"
type: docs
weight: 1910
url: /de/net/aspose.svg.builder/svgbuilderextensions/points/
---
## Points<TBuilder>(*this TBuilder, params double[]*) {#points}

Setzt das 'points'-Attribut für ein SVG-Element mithilfe eines Arrays von Double-Werten.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params double[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| points | Ein Array von Doubles, das die Punkte darstellt (muss eine gerade Anzahl sein). |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn eine ungerade Anzahl von Punkten übergeben wird. |

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Points<TBuilder>(*this TBuilder, params PointF[]*) {#points_1}

Setzt das 'points'-Attribut für ein SVG-Element mithilfe eines Arrays von PointF-Objekten.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params PointF[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| points | Ein Array von PointF-Objekten, das die Punkte darstellt. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
