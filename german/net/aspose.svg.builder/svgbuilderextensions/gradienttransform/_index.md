---
title: "SVGBuilderExtensions.GradientTransform"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions GradientTransform‑Methode. Setzt das gradientTransform‑Attribut für ein Gradient‑Element."
type: docs
weight: 980
url: /de/net/aspose.svg.builder/svgbuilderextensions/gradienttransform/
---
## SVGBuilderExtensions.GradientTransform<TBuilder> method

Setzt das Attribut 'gradientTransform' für ein Gradient-Element.

```csharp
public static TBuilder GradientTransform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG‑Element‑Builder, auf den das Attribut angewendet wird. |
| konfigurieren | Eine Funktion, um den SVG‑Transform‑Builder zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
