---
title: "SVGBuilderExtensions.RefY"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions RefY-metoden. Ställer in refY-attributet för ett SVG-element"
type: docs
weight: 1940
url: /sv/net/aspose.svg.builder/svgbuilderextensions/refy/
---
## RefY<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#refy_1}

Ställer in 'refY'-attributet för ett SVG-element.

```csharp
public static TBuilder RefY<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRefCoordinatesAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| value | Referens‑Y‑koordinaten. |
| type | Typen av längdenhet (standard är pixlar). |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRefCoordinatesAttributeSetter](../../irefcoordinatesattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RefY<TBuilder>(*this TBuilder, [VerticalPosition](../../verticalposition/)*) {#refy}

Ställer in 'refY'-attributet för ett SVG-element med en fördefinierad vertikal position.

```csharp
public static TBuilder RefY<TBuilder>(this TBuilder builder, VerticalPosition value)
    where TBuilder : ISVGElementBuilder, IRefCoordinatesAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| value | Den fördefinierade vertikala positionen. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [VerticalPosition](../../verticalposition/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRefCoordinatesAttributeSetter](../../irefcoordinatesattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
