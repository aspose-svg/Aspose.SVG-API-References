---
title: "SVGBuilderExtensions.Dx"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions Dx Methode. Setzt das dx-Attribut, um die horizontale Position jedes Zeichens im Text anzupassen."
type: docs
weight: 770
url: /de/net/aspose.svg.builder/svgbuilderextensions/dx/
---
## Dx<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#dx}

Setzt das Attribut 'dx', um die horizontale Position jedes Zeichens im Text anzupassen.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| type | Der Typ der Längeneinheit für die Werte. |
| values | Die horizontalen Anpassungswerte für jedes Zeichen. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

## Hinweise

Diese Methode ermöglicht eine feine Kontrolle über den horizontalen Abstand der Zeichen im Text.

### Siehe auch

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dx<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dx_1}

Setzt einen einzelnen horizontalen Anpassungswert für den Textinhalt.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Der horizontale Anpassungswert. |
| type | Der Typ der Längeneinheit für den Wert. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

## Hinweise

Diese Methode setzt das 'dx'-Attribut mit einem einzelnen Wert und passt die horizontale Position des Textinhalts an.

### Siehe auch

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
