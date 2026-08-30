---
title: "SVGBuilderExtensions.FontKerning"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions FontKerning-metod. Ställer in font-kerning-attributet för ett SVG-element med ett numeriskt värde och en specifik längdtyp"
type: docs
weight: 880
url: /sv/net/aspose.svg.builder/svgbuilderextensions/fontkerning/
---
## FontKerning<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#fontkerning_1}

Ställer in attributet 'font-kerning' för ett SVG-element med ett numeriskt värde och en specifik längdtyp.

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| value | Font-kerningvärdet att sätta. |
| type | Längdtypen (t.ex. px, em). |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## FontKerning<TBuilder>(*this TBuilder, [Kerning](../../kerning/)*) {#fontkerning}

Ställer in attributet 'font-kerning' för ett SVG-element med ett fördefinierat kerning‑värde.

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, Kerning value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| value | Det fördefinierade kerningvärdet att sätta. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [Kerning](../../kerning/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
