---
title: "SVGBuilderExtensions.Y"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions Y-Methode. Setzt das y-Attribut für ein SVG-Element."
type: docs
weight: 2400
url: /de/net/aspose.svg.builder/svgbuilderextensions/y/
---
## Y<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#y_1}

Setzt das Attribut 'y' für ein SVG-Element.

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IYAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| value | Der Wert für das 'y'-Attribut. |
| type | Der Typ der Längenmessung (Standard ist Pixel). |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IYAttributeSetter](../../iyattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Y<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#y}

Setzt das Attribut 'y' zur Positionierung des Textinhalts entlang der y-Achse.

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| type | Der Typ der Längeneinheit für die Werte. |
| values | Die y-Achsen-Positionswerte. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

## Hinweise

Diese Methode setzt das Attribut 'y', das die vertikale(n) Position(en) des Textelements bestimmt.

### Siehe auch

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
