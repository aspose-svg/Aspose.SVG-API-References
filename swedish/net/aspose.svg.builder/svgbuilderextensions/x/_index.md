---
title: "SVGBuilderExtensions.X"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions X metod. Ställer in x‑attributet för ett SVG-element."
type: docs
weight: 2360
url: /sv/net/aspose.svg.builder/svgbuilderextensions/x/
---
## X<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#x_1}

Ställer in attributet 'x' för ett SVG-element.

```csharp
public static TBuilder X<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IXAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| value | Värdet för 'x'-attributet. |
| type | Typen av längdmätning (standard är pixlar). |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IXAttributeSetter](../../ixattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## X<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#x}

Ställer in attributet 'x' för att positionera textinnehållet längs x‑axeln.

```csharp
public static TBuilder X<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| type | Typen av längdenhet för värdena. |
| values | Värdena för x‑axelns position. |

### Returvärde

Byggarinstansen för kedjning.

## Anmärkningar

Denna metod sätter 'x'-attributet, vilket bestämmer den horisontella positionen/positionerna för text‑elementet.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
