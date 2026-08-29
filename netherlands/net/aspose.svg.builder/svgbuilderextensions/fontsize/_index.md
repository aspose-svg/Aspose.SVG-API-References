---
title: "SVGBuilderExtensions.FontSize"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions FontSize-methode. Stelt het font-size‑attribuut in voor een SVG‑element met behulp van een numerieke waarde en een specifiek lengtype"
type: docs
weight: 890
url: /nl/net/aspose.svg.builder/svgbuilderextensions/fontsize/
---
## FontSize<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#fontsize_1}

Stelt het 'font-size' attribuut voor een SVG-element in met een numerieke waarde en een specifiek lengtetype.

```csharp
public static TBuilder FontSize<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| waarde | De te zetten lettergroottewaarde. |
| type | Het length type (bijv. px, em). |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## FontSize<TBuilder>(*this TBuilder, [FontSize](../../fontsize/)*) {#fontsize}

Stelt het 'font-size' attribuut voor een SVG-element in met een vooraf gedefinieerde font-grootte waarde.

```csharp
public static TBuilder FontSize<TBuilder>(this TBuilder builder, FontSize value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| waarde | De vooraf gedefinieerde lettergroottewaarde die moet worden ingesteld. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [FontSize](../../fontsize/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
