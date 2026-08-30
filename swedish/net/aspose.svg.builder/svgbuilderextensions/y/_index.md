---
title: "SVGBuilderExtensions.Y"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions Y-metod. Ställer in y-attributet för ett SVG-element"
type: docs
weight: 2400
url: /sv/net/aspose.svg.builder/svgbuilderextensions/y/
---
## Y<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#y_1}

Ställer in attributet 'y' för ett SVG-element.

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IYAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| value | Värdet för 'y'-attributet. |
| type | Typen av längdmätning (standard är pixlar). |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IYAttributeSetter](../../iyattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Y<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#y}

Ställer in 'y'-attributet för att positionera textinnehållet längs y-axeln.

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| type | Typen av längdenhet för värdena. |
| values | y-axelns positionsvärden. |

### Returvärde

Byggarinstansen för kedjning.

## Anmärkningar

Denna metod sätter 'y'-attributet, vilket bestämmer den vertikala positionen/positionerna för textelementet.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
