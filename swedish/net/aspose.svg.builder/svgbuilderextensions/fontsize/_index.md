---
title: "SVGBuilderExtensions.FontSize"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions FontSize‑metoden. Ställer in font‑size‑attributet för ett SVG‑element med ett numeriskt värde och en specifik längdtyp."
type: docs
weight: 890
url: /sv/net/aspose.svg.builder/svgbuilderextensions/fontsize/
---
## FontSize<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#fontsize_1}

Ställer in attributet 'font-size' för ett SVG-element med ett numeriskt värde och en specifik längdtyp.

```csharp
public static TBuilder FontSize<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| value | Font‑storleksvärdet att ange. |
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

## FontSize<TBuilder>(*this TBuilder, [FontSize](../../fontsize/)*) {#fontsize}

Ställer in attributet 'font-size' för ett SVG-element med ett fördefinierat teckenstorleksvärde.

```csharp
public static TBuilder FontSize<TBuilder>(this TBuilder builder, FontSize value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| value | Det fördefinierade font‑storleksvärdet att ange. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [FontSize](../../fontsize/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
