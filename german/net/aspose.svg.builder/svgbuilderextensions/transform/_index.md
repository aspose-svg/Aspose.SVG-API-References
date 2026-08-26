---
title: "SVGBuilderExtensions.Transform"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions Transform-Methode. Setzt das transform-Attribut für ein SVG-Element."
type: docs
weight: 2260
url: /de/net/aspose.svg.builder/svgbuilderextensions/transform/
---
## SVGBuilderExtensions.Transform<TBuilder> method

Setzt das Attribut 'transform' für ein SVG-Element.

```csharp
public static TBuilder Transform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, ITransformAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Eine Funktion, um die SVG-Transformation zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITransformAttributeSetter](../../itransformattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
