---
title: "SVGBuilderExtensions.AddAnimate"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddAnimate Methode. Fügt dem Builder eine Animate-Element-Konfiguration hinzu."
type: docs
weight: 30
url: /de/net/aspose.svg.builder/svgbuilderextensions/addanimate/
---
## SVGBuilderExtensions.AddAnimate<TBuilder> method

Fügt dem Builder eine 'animate'‑Elementkonfiguration hinzu.

```csharp
public static TBuilder AddAnimate<TBuilder>(this TBuilder builder, 
    Action<SVGAnimateElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IBaseAnimationElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'animate'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGAnimateElementBuilder](../../svganimateelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IBaseAnimationElementBuilder](../../ibaseanimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
