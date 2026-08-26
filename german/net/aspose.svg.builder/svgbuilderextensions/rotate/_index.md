---
title: "SVGBuilderExtensions.Rotate"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions Rotate-Methode. Setzt Rotationswinkel für einzelne Zeichen oder Segmente des Textinhalts."
type: docs
weight: 2000
url: /de/net/aspose.svg.builder/svgbuilderextensions/rotate/
---
## Rotate<TBuilder>(*this TBuilder, params double[]*) {#rotate_1}

Setzt Rotationswinkel für einzelne Zeichen oder Segmente des Textinhalts.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| values | Ein Array von Rotationswinkeln in Grad. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

## Hinweise

Diese Methode setzt das 'rotate'-Attribut mit mehreren Werten und ermöglicht die individuelle Drehung jedes Zeichens oder Textsegments.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Rotate<TBuilder>(*this TBuilder, double*) {#rotate}

Setzt einen einzelnen Rotationswinkel für den gesamten Textinhalt.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, double value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Der Rotationswinkel in Grad. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

## Hinweise

Diese Methode setzt das 'rotate'-Attribut mit einem einzelnen Wert und wendet denselben Rotationswinkel auf den gesamten Textinhalt an.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
